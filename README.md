# nextdeploy-sop

This project includes exploitation and deployment scripts for the [nextdeploy projet](https://github.com/ricofehr/nextdeploy).

Available commands:
* backupcontroller: backup openstack controller database
* backupnextdeploy: make and retrieve a backup of nextdeploy project
* bundleinstall: execute a "bundle install" into rest api folder
* checkcompute: check openstack compute services
* checkcontroller: check openstack controller services
* checkglance: check openstack glance services
* checkneutron: check openstack neutron services
* checknextdeploy: check nextdeploy node services
* cleangrafana: clean nightly temporary pngs generated by grafana
* cleanossec: clean nightly the vms traced by ossec
* deploycli: make and deploy a package for the nextdeploy cli command
* deployclitest: make and deploy a package for nightly build of the nextdeploy cli command
* gitlabreconfigure: execute a "gitlab-reconfigure" on gitlab webapp
* listbackupgitlab: list gitlab archives
* listbackupnextdeploy: list backup archives
* listbackuppuppet: list puppetmaster archives
* listtag: list the tags for nextdeploy project
* maintenanceapi: put the api in offline mode
* maintenanceoff: disable all offline mode
* maintenancevms: put the vms in offline mode
* maintenanceui: put the webui in offline mode
* puppetstart: enable puppet agents on openstack nodes, and nextdeploy node
* puppetstop: disable puppet agents on openstack nodes, and nextdeploy node
* pullnextdeploy: make a git pull on the remote prod nextdeploy management node
* rakemigrate: execute ruby on rails migration on the rest api
* rebuildember: rebuild the application.js for the ember webui
* rebootcompute: reboot compute nodes
* rebootcontroller: reboot the controller node
* rebootglance: reboot glance node
* rebootneutron: reboot neutron node
* rebootnextdeploy: restart services into nextdeploy manager node
* restartcompute: restart all compute services
* restartcontroller: restart all controller services (keystone, horizon, api, ...)
* restartgitlab: restart gitlab services
* restartglance: restart glance services
* restartmemcached: restart memcached service for the webui
* restartneutron: restart all neutron services
* restartnextdeploy: restart all nextdeploy manager node services
* restartnginx: restart nginx, the revers-proxy of nextdeploy
* restartovpn: restart openvpn service
* restartpuma: restart the rails web server
* updatenodes: launch puppet agent interactively on the remote nodes
* yardoc: generate documentation for the rest api
