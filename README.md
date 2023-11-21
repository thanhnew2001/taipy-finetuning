# taipy-finetuning
- Run the notebook in 3090
- Run the quantization with the following command: ct2-transformers-converter --model thanhnew2001/starcoder-7b-taipy5 --output_dir taipy6-ct2 --force --copy_files tokenizer.json tokenizer_config.json  special_tokens_map.json .gitattributes --quantization int8_float16 --trust_remote_code
- Run the inference

