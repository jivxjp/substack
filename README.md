# substack

This repo captures the writing process for posts on jivx.substack.com through drafts and LLM-enhanced editing.

The author creates a draft under `posts` with a directory corresponding to the date the draft was created.

Once the draft is finished, a LLM edits it using the prompt in `post.md` under `prompts` directory. It sometimes require some manual edit on top and then saved to as `post.md` in the date directory.

The draft is used to generate sutra-like quotes throughout the posts using the `sutras.md` prompt. They are saved under `sutras.md` in the date directory.

The image generated for each post uses `image.md` prompt. The images are not saved here, only uploaded to Substack once.

The lyrics is generated using the `lyrics.md` prompt while the song is generated using [suno](https://suno.com).

Each post starts with [a scientific unicode](https://unicode-explorer.com/b/1D400).

The video for the song is made by Final Cut Pro with [stereodrift](https://github.com/stereoDrift/stereoDrift.github.io) as the visualizer.
