# home
Home configuration

## User System Configuration

**Note:** Replace the IP passed to Ansible with the IP of the system you intend
to configure.

**Note:** SSH should already be configured and usable for the intended host.
An SSH key must be used rather than a password.

```sh
ansible ansible/user_system.yml -i "192.168.0.1," \
	--extra-vars "target_system_role = debian"
```

#### Currently Configured Target Systems:

- `ubuntu`
