### 🧾 PR Checklist

Please verify each of the following before submitting this PR:

- [ ] Chart.yaml version number matches the version number specified in the version comment.
- [ ] No duplicate code blocks have been introduced (DRY principle).
- [ ] No duplicate ranges or conditionals are introduced in Helm templates.
- [ ] All unit test descriptions follow the format:  
      `should <verb> <resource/role> [to <target>] when <condition>`

> Example: `should grant roles/cloudfunctions.developer to developer SA when cf_deployment is enabled`
