# Accelerator Log

## Options
```json
{
  "greeting" : "Hello",
  "projectName" : "hello-ytt"
}
```
## Log
```
┏ engine (Chain)
┃  Info Running Chain(YTT, UniquePath)
┃ ┏ engine.transformations[0] (YTT)
┃ ┃ Debug Wrote values file with json content:   {"artifactVersion":"0.0.1-beta","greeting":"Hello","artifactId":"hello-ytt","projectName":"hello-ytt"}
┃ ┗  Info Shelling out to YTT with args: [ytt, -f, /tmp/ytt-input10985608569729528071, --data-values-file, /tmp/accelerator-options18316465088790615331.json, --output-files, /tmp/ytt-output1660933963057274006]
┗ ╺ engine.transformations[1] (UniquePath)
```
