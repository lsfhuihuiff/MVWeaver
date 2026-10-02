# Creative Bridge Dataset

1,861 song–music-video pairs: 1,841 training samples and 20 test samples.

- `annotations_train.jsonl`: training set.
- `annotations_test.jsonl`: test set.

Each UTF-8 JSONL line contains one sample, including its `split`, `youtube_url`, video metadata, and `annotation`. The annotation contains six global creative-planning cards in `global_mv_planning` and ordered story beats in `structure_beat_planning`, with their `mv_choice`, `song_evidence`, and `association_chain` fields.
