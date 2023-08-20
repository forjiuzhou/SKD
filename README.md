# SKD

mkdir log
python main.py -a resnet18 --b 256 --workers 8 --opt-level O0 --T 4 --alpha 0.9 --distillation  --SKD --log_str log ./
