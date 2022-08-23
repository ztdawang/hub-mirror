
github上:

- 开启 `Settings`-`Options`-`Features` 中的 `Issues` 功能

- 在 `Settings`-`Secrets`-> 'action' -> 'new repository secret' 新建 `DOCKER_USERNAME`（你的 hub.docker.com 用户名） 和 `DOCKER_TOKEN`（你的 hub.docker.com 密码） 两个 Secrets

- 在 `Issues`-`Labels` 添加三个 label ：`hub-mirror`、`success`、`failure`

- 在 `Actions` 里选择 `hub-mirror` ，如果Workflow不是Enable的话，在右边 `···` 菜单里选择 `Enable Workflow`

- 最后，新建issue，记得按照上面提示的格式修改json内容即可，标题不用改。 然后就会自动执行工作流.................
