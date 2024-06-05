inputs_cn = """
高东辉 来啊[laugh]快活啊inputs_cn = """
高[laugh]东[laugh]辉[laugh]来啊[laugh]来啊[laugh]来啊[laugh]来啊[laugh]
""".replace('\n', '')

params_refine_text = {
  'prompt': '[oral_2][laugh_0][break_4]'
} 
audio_array_cn = chat.infer(inputs_cn, params_refine_text=params_refine_text)
# audio_array_en = chat.infer(inputs_en, params_refine_text=params_refine_text)

torchaudio.save("output3.wav", torch.from_numpy(audio_array_cn[0]), 24000)，
停顿啊[uv_break]语气词啊等副语言现象[uv_break]。这个韵律超越了许多开源模型[uv_break]。
请注意，chat T T S 的使用应遵守法律和伦理准则，避免滥用的安全风险。[uv_break]'
""".replace('\n', '')

params_refine_text = {
  'prompt': '[oral_2][laugh_0][break_4]'
} 
audio_array_cn = chat.infer(inputs_cn, params_refine_text=params_refine_text)
# audio_array_en = chat.infer(inputs_en, params_refine_text=params_refine_text)

torchaudio.save("output3.wav", torch.from_numpy(audio_array_cn[0]), 24000)
