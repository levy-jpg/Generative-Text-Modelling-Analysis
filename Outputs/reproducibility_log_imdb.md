Run date: 2026-04-01 20:58:41
Device: cuda
Dataset: imdb
Train/Val/Test sizes: 22500 / 2500 / 25000
Vocab cap: 20000
SEQ_LEN: 64
Batch size: 128

Baseline (LSTM):
- emb=256 hidden=512 layers=2 dropout=0.2 lr=2e-3
- epochs=8
- test_loss=4.9071
- test_ppl=135.25

Main (Transformer):
- emb=256 heads=4 layers=4 ff=1024 dropout=0.1 lr=2e-4
- epochs=12
- test_loss=4.9466
- test_ppl=140.70

Sustainability notes:
- model sizes constrained via vocab cap and sequence length
- bounded training time via max_minutes
- baseline/main comparison used instead of scaling model size aggressively
