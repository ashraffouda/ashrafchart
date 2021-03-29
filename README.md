### Packaging
- Do `helm lint charts/<your-chart-name>`
- Regenerate the packages `helm package -u charts/<your-chart-name>`
- Regenerate index.yaml `helm repo index --url https://ashraffouda.github.io/ashrafchart/ --merge index.yaml .`
- Push your changes