# Replay chrome recorder

因工作遇到相關情境，測試一下 Chrome Recorder 錄製腳本的使用。

## Getting started
- (Optional) Record a script via Chrome Recorder
    - `Chrome -> Devtools -> Recorder -> Create a new record -> export as a JSON script -> replace ./script_samples/recording.json`
- Run `node main.js`

## Common errors
- TimeoutError: Navigation timeout of 5000 ms exceeded
    - Setup timeout argument in "Replay settings" of Chrome Recorder, or change the value of global variable `TIMEOUT`.
