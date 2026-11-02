# 第3回 解答

## 演習

- 第1回（素のLLM）とエージェントの回答の違い：
  - 用語集の内容がエージェントからの回答のベースとなっていた 
- `--trace` で見えたツール呼び出し（ツール名と引数）：
  - [tool call]   search_glossary({'query': 'LoRA'})
  - [tool call]   search_glossary({'query': 'QLoRA'}) 
- 1つの質問での LLM 呼び出し回数（`requests`）：
  - 2回
  - [usage] RunUsage(cost=Decimal('0.0007907'), details={'text_prompt_tokens': 1194}, input_text_tokens=1194, input_tokens=1194, output_tokens=173, requests=2, tool_calls=2)   
- 追加したツールと、docstring に書いた説明：
  - make_quiz を追加
  - docstring には「指定した回の用語から1つ選び、確認問題と答えを返す。「第2回の確認問題を出して」のように、復習用の問題を求められた時に使う。　と記載

## 宿題

- 取り組んだレベル：基礎 / 実装 / 発展
- やったこと：
- 結果：
- 気づき・疑問：
