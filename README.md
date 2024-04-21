<!--
 * @Author: Night-stars-1 nujj1042633805@gmail.com
 * @Date: 2024-04-21 13:14:53
 * @LastEditTime: 2024-04-21 14:25:04
 * @LastEditors: Night-stars-1 nujj1042633805@gmail.com
-->
# Changelog Generator Action

## Outputs

`changelog`

## Example usage

```yaml
- name: test
id: generate_changelog
uses: Night-stars-1/changelog-generator-action@main

- name: Use the output
run: |
    echo "Generated changelog:"
    echo "${{ steps.generate_changelog.outputs.changelog }}"
```

Please see the workflow in `.github/workflows` of this repo to see how the job steps are setup.
