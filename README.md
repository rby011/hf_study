# hf_study

I'm getting tired of reading papers and thought it might be a good idea to take a break and visually explore the latest trends. There seem to be various libraries out there, but considering that Hugging Face is partnering with Google, it seems like a good idea to focus on this. I've decided to spend about a month looking into this. In the meantime, it seems like a good idea to attend seminars by AI Factory one by one.

## Environment Setup

git lfs install

```bash
# install
curl -s https://packagecloud.io/install/repositories/github/git-lfs/script.deb.sh | sudo bash
apt-get install git-lfs

# init
git lfs install
```

#### transformers install with pip

```bash
# create virutal environment in this project directory
python -m venv .env

# activate virtual env
source .env/bin/activate

# pip install diffusers['torch'] transformers
```

## References

- [Hugging Face - Documentation](https://huggingface.co/docs)
- [인공지능팩토리 (aifactory.space)](https://aifactory.space/learning)
