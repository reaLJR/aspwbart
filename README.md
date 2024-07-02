ASPWBART - Answer Set Programming Weighted Bipolar Argumentation Reasoning Tool

-asp 
  clingo input.af preferred_penalty.lp --opt-mode=optN --quiet=1
-python 
  --main.py 主程序
  --answer.py 供main.py调用
  --evaluate.py 单独用于测试效率
