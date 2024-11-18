# Commands for HDC 

### ImageNet
```bash
python eval_diff.py --dataset imagenet --split test --n_trials 1 \
  --to_keep 500 50 10 1 --n_samples 50 100 500 1000 \
  --prompt_path prompts/imagenet_hierarchy_prompts.csv \
  --strat 1 --info_dir imagenet_hierarchy \
  --k 0.5 
```

