# Open Imagery

Free AI image generation

# Getting key

# Due to internal issues you are requested to use the key `test` for the time being.

Join the discord server at 
https://discord.gg/bUQdAujVYd

follow the instructions to get a key.

# Image generation

## Base url: https://ai.sitius.ir

## POST /v1/generate/
### Headers
#### auth: "API KEY"
### JSON Data
```json
{
  "prompt": "prompt",
  "model": "model",
  "negative_prompt": "negative_prompt/things you dont want",
  "steps": 40,
  "cfg_scale": 7,
  "sampler": "sampler"
}
```

This will return a jobid

## GET /v1/image/{jobid}/
This returns the image.

## GET /v1/models/
Get available models

## GET /v1/samplers/
Get available samplers
