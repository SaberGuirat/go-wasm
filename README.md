cp $(tinygo env TINYGOROOT)/targets/wasm_exec.js .
or
cp "$(go env GOROOT)/misc/wasm/wasm_exec.js" .
tinygo build -o main.wasm -target wasm ./main.go
