# 🥷✨ Semgrep Rules - for Security Pros

Rules:
- ✅ Security relevant patterns only
- ❌ No performance, micro optimizations and other noise

Languages:
- Solidity

- [⇒ rules](./rules) - 👈🚀 Is the **active** ruleset. Be smart, use this ☝️<br>
  - Solidity
- [⇒ _dev](./_dev) - 🧑‍🔬💥 Experimental rules. Would not use.


## ✨ Integrations

### CLI

```shell
tintin@:~/workspace/solidity/project-under-audit|⇒  semgrep --exclude="**mock**,**test**" --severity=WARNING --severity=ERROR -c /path_to_this_repo/rules .  
```

### VSCode

<video src="https://github.com/returntocorp/semgrep-vscode/assets/626337/b08d17b6-3fb7-46fe-93ec-09f9257d58a3" controls="controls">
</video>

1. install https://marketplace.visualstudio.com/items?itemName=Semgrep.semgrep
2. configure:
   1. `semgrep.scan.exclude` 👉 `**/node_modules/**`, `**test**`, `**mock**`
   2. `semgrep.scan.configuration` 👉 `auto`, `/path_to_this_repo/rules`


## ⭐ Credits

Contribute, share! 🤗❤️

- [@tintinweb](https://github.com/tintinweb)
- [decurity/semgrep-smart-contracts](https://github.com/Decurity/semgrep-smart-contracts)
- [you? 🥹](https://github.com/tintinweb)
