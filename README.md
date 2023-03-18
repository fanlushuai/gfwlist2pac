# gfwlist2pac
Automatically convert gfwlist to pac everyday

Just use https://raw.githubusercontent.com/fanlushuai/gfwlist2pac/master/gfwlist.pac

Proxys / CDNs:

- jsDelivr: https://cdn.jsdelivr.net/gh/fanlushuai/gfwlist2pac@master/gfwlist.pac
- FastGit: https://raw.fastgit.org/fanlushuai/gfwlist2pac/master/gfwlist.pac
- GitHub Proxy: https://ghproxy.com/https://github.com/fanlushuai/gfwlist2pac/blob/master/gfwlist.pac
- 7ED SERVICE: https://raw.sevencdn.com/fanlushuai/gfwlist2pac/master/gfwlist.pac

## Self-host Usage

1. Fork
2. Modify action permission
	1. github path: settings > actions > General > Workflow permissions

	2. open read and write permissions

3. define your self `Proxy` variable for genpac

	1. gihub path：settings > secrets and variables > actions 

	2. new repository variable  

		name: `PROXY`

		value: `SOCKS5 127.0.0.1:7890 or other what you want`
