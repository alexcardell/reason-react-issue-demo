# reason-react-issue-demo

## Repo demonstrating [reasonml/reason-react#352](https://github.com/reasonml/reason-react/issues/352)

### Steps to reproduce
- `yarn install`
- `yarn build`
- Notice this log output:
  ```
  Building src/ReactDOMRe.mlast.d
  Building src/ReactDOMRe.cmj
  ```
- `rm -rf node_modules`
- `yarn install`
- `yarn server`
- Notice errors in webpack-dev-server logs
- Hope the reason-react discord can shed light on why
