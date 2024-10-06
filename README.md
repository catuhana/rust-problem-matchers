# Rust Problem Matchers

GitHub Action to set-up [Problem Matchers](https://github.com/actions/toolkit/blob/main/docs/problem-matchers.md) for Rust.

<picture>
  <source media="(prefers-color-scheme: light)" srcset=".github/assets/demo.png" />
  <source media="(prefers-color-scheme: dark)" srcset=".github/assets/demo-dark.png" />
  <img alt="Demo Screenshot" src=".github/assets/demo.png">
</picture>

## Usage

Create a new step and add this action to the `uses` field:

```yaml
- name: Set-up Rust Problem Matchers
  uses: catuhana/rust-problem-matchers@v1
```
