# playbook-action
gbraad's Dotfiles `playbook` action
===================================


Use dotfiles' `playbook`-command for Ansible playbook execution

### Usage

```yaml
      - name: Setup environment
        uses: gbraad-dotfiles/install-action@main
        
      - name: Excute example notebook
        uses: gbraad-dotfiles/playbook-action@main
        with:
          notebook: examples/playbook.yaml
          command: execute
```
