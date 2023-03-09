# chatgpt-request

https://openai.com/blog/openai-api

``` py
import openai

OPENAI_API_KEY = ""

openai.organization = "org-UYnm4WlMSWnaQeHSKhi2wnys"
openai.api_key = OPENAI_API_KEY

completions = openai.Completion.create(
    engine="text-davinci-003",
    prompt="Write me a song",
    max_tokens=1024,
    n=1,
    stop=None,
    temperature=0.5,
)

print(completions.choices[0].text)
 ```
