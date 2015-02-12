* When running in a local lxc environment, appscale is accessible even before `juju expose appscale` is run.
* When running in aws, the expose command needs to be run before appscale starts. This is because the `appscale up` command uses ssh.
* For some reason, none of the juju-specific environment variables are set when debugging hooks.
* In the amazon environment, /root/.ssh/authorized_keys seems to get emptied when debugging hooks.
* `$HOME` seems to get reset back to /home/ubuntu (even running as root) at the start of every hook.

