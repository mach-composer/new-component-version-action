# publish-action


```yml
      - name: Mach Composer Cloud - Register version
        uses: mach-composer/new-component-version-action@main
        with:
          organization: "your-organization"
          project: "project-key"
          component: "component-key"
          client_id: ${{ secrets.MCC_CLIENT_ID }}
          client_secret: ${{ secrets.MCC_CLIENT_SECRET }}
```
