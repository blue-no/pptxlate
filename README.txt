使い方:
  python -m pptxlate コマンド 変換するファイルのパス 保存先のパス [オプション]

コマンド:
  han                全角文字を半角文字に変換する
  zen                半角文字を全角文字に変換する

オプション:
  -k, --kana         カナ文字を変換する
  -n, --num          数字を変換する
  -a, --alph         アルファベットを変換する
  -st, --skip-title  タイトル欄の文字を無視する

使用例:
デスクトップ上のinput.pptxのタイトル以外のカナ文字、数字を半角に変換し、output.pptxという名前で保存する
  python -m pptxlate han Desktop/intput.pptx Desktop/output.pptx -k -n -st
