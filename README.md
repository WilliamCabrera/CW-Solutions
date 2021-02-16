"# CW-Solutions" 

After installing Husky and git-commit-message-checker go to node_modules/git-commit-message-checker/lib check-git-commit-msg.js and replace line number: 68 as follow

//const pattern = args['pattern'] ? args['pattern'] : DEFAULT_PATTERN; const pattern = DEFAULT_PATTERN;
