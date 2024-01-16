# Development-Environment-Configuration

## SSH
 - config.template
   - replace [work-key-file-name]
   - replace [personal-key-file-name]
 - .gitconfig.template
   - replace [First Last]
   - replace [work directory]
   - replace [personal directory]
 - [work]/.gitconfig.personal.template 
   - replace [work email]
 - [personal]/.gitconfig.personal.template 
   - replace [personal email]
 - .zshrc.template
   - replace USER_PATH=[first.last]
   - replace [work-key-file-name]
   - replace [personal-key-file-name]

## Other
 - .zshrc.template
   - replace export GITLAB_TOKEN_OPA=[token]
   - replace export GITLAB_TOKEN_MW=[token]
   - replace export AIRTABLE_TOKEN=[token]
   - (@James) uncomment the 'HISTFILE="$HOME/.zsh_history.$(echo $$)"'
