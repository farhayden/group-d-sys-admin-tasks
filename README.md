# Group-D-System-Admin-Tasks

Welcome to the group-d repository for operations engineering 2.

- Ticket documentation can be found in the ` Wiki ` section.

## Team Members

- Greg Seal
- Francis Hayden
 
 ## Useful Commands / Locations
 
 Refresh puppet on agent nodes ` sudo /opt/puppetlabs/bin/puppet agent --test ` alias: ` run-puppet `
 
 Site.pp (to manage modules run on each node) ` /etc/puppetlabs/code/environments/production/manifests/site.pp `
 
 Modules folder (add modules here) `/etc/puppetlabs/code/modules `
 
 ## Module Structure

```
 module_name
   ├── files
   ├── templates
   │      └── module_name.conf.erb
   └── manifests
          └── init.pp
```

