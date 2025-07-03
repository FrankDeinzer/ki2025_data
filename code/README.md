## Original repo: 
https://github.com/younader/Vesuvius-Grandprize-Winner


## Instructions
To train:
Adjust paths to labels and segments in top section of train_timesformer_og.py.

Then run:

```bash
python train_timesformer_og.py
```

Or to run inference on segments with the already trained model:

```bash
python inference_timesformer.py --model_path timesformer_weights.ckpt --segment_path path/to/Scroll5/PHerc172.volpkg/paths/ --segment_id 20241113090990 2024111308080
```