# whisperzh
Transcripts of Andrej Karpathy's [Neural Networks: Zero to Hero course lectures](https://www.youtube.com/playlist?list=PLAqhIrjkxbuWI23v9cThsA9GvCAUhRvKZ).

## Tools
1. [yt-dlp](https://github.com/yt-dlp/yt-dlp):
```bash
yt-dlp --yes-playlist --x --audio-format mp3 {playlist_link}`
```
2. [openai/whisper](https://github.com/openai/whisper):
```bash
whisper --language en --model large -o {out_dir} -- {mp3_file}
```

## Acknowledgements
- [@karpathy](https://github.com/karpathy)'s [nn-zero-to-hero](https://github.com/karpathy/nn-zero-to-hero)
- [@averkij](https://github.com/averkij)'s [karcaps](https://github.com/averkij/karcaps)
