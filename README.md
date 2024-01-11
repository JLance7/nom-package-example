# Package example
npm package example

## Usage
```bash
npm i <package_name>
```
import examples in example/

## Development
clone repo
```bash
npm i
tsc --watch
npm link
```
go to test example/example.ts
npm link <package_name>
import/update code
run:
```bash
npx ts-node example.ts
```

## Testing
```bash
npm test
```

## Deployment
```bash
npm build
npm publish
```
