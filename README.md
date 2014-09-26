# Runp

Ansible role to embed runp module.

## Example Playbook

After declaring `runp` role:

    - hosts: all
      roles:
         - runp
		 
You can use condition base on ``--check`` option

	- tasks:
	  - debug: msg="Not when in check mode"
		when: run_mode

## Alternative way

Since 1.3 Ansible has jinja2 filter `skipped`

## License

MIT

## Author Information

Thierry Delamare
