# hf_study

허깅페이스를 중심으로 diffusion, llm 에 대한 학습 정리 

## Environment Setup

#### transformers install with pip

현재 프로젝트내에 모든 패키지를 설치하는 구조로 만들거임

```bash
# create virutal environment in this project directory
python -m venv .env

# activate virtual env
source .env/bin/activate

# install
pip install diffusers['torch'] transformers
```

#### jupyter

VSCode 에서 jupyter 연결해서 쓰는데 필요한 패키지들 설치함

```bash
pip install ipykernel

pip install ipywidgets
```

#### lfs install

git lfs 필요할 수도 있을 거 같아서 설치함

```bash
# install
curl -s https://packagecloud.io/install/repositories/github/git-lfs/script.deb.sh | bash
apt-get install git-lfs

# init
git lfs install

# config
git config --global user.email "chsun.song@gmail.com"
git config --global user.name "rby011"
```

## References

- [Hugging Face - Documentation](https://huggingface.co/docs)
- [인공지능팩토리 (aifactory.space)](https://aifactory.space/learning)
