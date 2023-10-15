# Cloud City Crafted GitHub Action: Publish Image

A GitHub composite action to publish @cloud-city-crafted-images to the GitHub Container Registry.

## ⌨️ Usage

```yaml
- name: Build and Publish Cloud City Crafted Image
  uses: cloud-city-crafted-images/publish-image@v1
  with:
    github-token: ${{ github.token }}
```

## 🪪 License

This repository is [MIT licensed](./LICENSE).
