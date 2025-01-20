
![demo gif](https://github.com/mindcrunch4u/cli-search/blob/main/about/stay%20in%20cli.gif)

## Preparation

```
git clone https://github.com/mindcrunch4u/cli-search
cd cli-search

python -m venv env
source env/bin/activate

pip install -r requirements.txt
chmox +x howto
```

Make sure to specify the correct `base_url` of your API provider:
`vim howto`
- OpenAI: `https://api.openai.com/v1`
- Another Provider: `https://hk.xty.app/v1`

(Optional)
```
export HTTP_PROXY=""
export HTTPS_PROXY=""
```

## Usage

```
export OPENAI_KEY="Your OpenAI Key"
./howto download an entire directory recursively using wget?
```
