# publish-action


```yml
      - name: Mach Composer Cloud - Register version
        uses: mach-composer/publish-action@main
        with:
          organization: "your-organization"
          project: "project-key"
          component: "component-key"
          version: ${GITHUB_SHA:0:7}
          client_id: ${{ secrets.MCC_CLIENT_ID }}
          client_secret: ${{ secrets.MCC_CLIENT_SECRET }}
```
