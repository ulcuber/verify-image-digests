WIP attempt to verify docker image tree

```bash
bash verify-image-digests <image-name> [digest]
```

See `get_docker_root_digest` function to know where to take root digest

Though digest argument is optional if you want just to verify tree

If you beleive root digest is uncopromised then no need to specify it in args

# TODO:

- Manifest canonicalization?
- tar vs tar.gz layers
- Relate local index.json/manifest.json with distribution manifest
