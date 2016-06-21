# Puppet

Ferramenta para gerenciamento de configuração

O comando `facter` Lista fatos do ambiente

```sh
[deployer@a1-halford-q-pla7 ~]$ facter
architecture => x86_64
augeasversion => 0.10.0
blockdevice_fd0_size => 0
blockdevice_hdc_size => 4294965248
blockdevice_sda_model => Virtual disk
blockdevice_sda_size => 10737418240
blockdevice_sda_vendor => VMware
blockdevice_sdb_model => Virtual disk
blockdevice_sdb_size => 524288000
blockdevice_sdb_vendor => VMware
blockdevices => fd0,hdc,sda,sdb
domain => host.intranet
facterversion => 1.7.0
filesystems => ext2,ext3,iso9660
fqdn => a1-halford-q-pla7.host.intranet
hardwareisa => x86_64
hardwaremodel => x86_64
hostname => a1-halford-q-pla7
id => deployer
interfaces => eth0,lo,sit0
ipaddress => 10.133.129.233
ipaddress6 => 2804:49c:c1aa:600:250:56ff:fe95:320f
ipaddress6_eth0 => 2804:49c:c1aa:600:250:56ff:fe95:320f
ipaddress_eth0 => 10.133.129.233
ipaddress_lo => 127.0.0.1
is_virtual => true
kernel => Linux
kernelmajversion => 2.6
kernelrelease => 2.6.18-194.11.4.el5
kernelversion => 2.6.18
lsbdistcodename => Final
lsbdistdescription => CentOS release 5.4 (Final)
lsbdistid => CentOS
lsbdistrelease => 5.4
lsbmajdistrelease => 5
lsbrelease => :core-3.1-amd64:core-3.1-ia32:core-3.1-noarch:graphics-3.1-amd64:graphics-3.1-ia32:graphics-3.1-noarch
macaddress => 00:50:56:95:32:0F
macaddress_eth0 => 00:50:56:95:32:0F
memoryfree => 1.88 GB
memoryfree_mb => 1928.55
memorysize => 1.96 GB
memorysize_mb => 2010.99
memorytotal => 1.96 GB
mtu_eth0 => 1500
mtu_lo => 16436
mtu_sit0 => 1480
netmask => 255.0.0.0
netmask_eth0 => 255.0.0.0
netmask_lo => 255.0.0.0
network_eth0 => 10.0.0.0
network_lo => 127.0.0.0
operatingsystem => CentOS
operatingsystemmajrelease => 5
operatingsystemrelease => 5.4
osfamily => RedHat
path => /usr/kerberos/bin:/usr/local/bin:/bin:/usr/bin:/sbin:/usr/sbin:/export/scripts:/home/deployer/bin
physicalprocessorcount => 2
processor0 => Intel(R) Xeon(R) CPU E5-2620 0 @ 2.00GHz
processor1 => Intel(R) Xeon(R) CPU E5-2620 0 @ 2.00GHz
processorcount => 2
ps => ps -ef
puppetversion => 2.7.20
rubysitedir => /usr/lib/ruby/site_ruby/1.8
rubyversion => 1.8.5
selinux => false
sshdsakey => AAAAB3NzaC1kc3MAAACBAKvF/XZxr/Npor+Husx9B6x3hXALPlFqjs76zfy/yYlkInQls+1S3/Hl2tOtfXTACAWO6VkB/+UI0fU4jrdtK3WdpXAv0w4rAkOafb2CIy3rz3ZtIFiSc6JG0Ig/ygtTKU749M2fM/QZevBrv6dbpo6ffQIJyXMoySXfkGx0hUdFAAAAFQCTOs7ujqUSiufM9looBsFfw/bifwAAAIB83Y/5Ki1d2/nY+3ca5n99DFBc0+gQzV9j/YhEZal+PR2U3f7dPg+6XjpLG8Xof2niEjYwF37l1nFxLfG6Hbhefp1JP614WLA0iNurGh5hkwkx5wYhhyB85QozKOHyDQ1DaW6GiFKP3Dm5M43VDRcWOUhjY0n++jAa/YyHMYViygAAAIEAiPCx/gxkQnzlkeIZVbDvoTFAe8muLPkSOkL28a4Y32XZ/kN7FBYIULg4D0Kx5B0Dn1CGjqDOSd26AZpHoKIkCWMb4qyZJYAsdVG6TnvC/oOjjtbpF9WaI4E214teXIyFvtbjw3oddq0Kv5DOrq5JKVJiym19s+rGHWyv8P3g5yE=
sshfp_dsa => SSHFP 2 1 2436dc4d9d502f8b741d5561ffb55de8c8ee0b48
SSHFP 2 2 9189c7c72dec5aad5e27731729de37e634fadcd3cf6dc2da57fa5f3edc03ccd3
sshfp_rsa => SSHFP 1 1 b6dd46693e1512d72bf4bb9c9c61585141b46f7c
SSHFP 1 2 caca2aa756789b1ce204ee4698609041303929d85419bcf9205767adb81cce57
sshrsakey => AAAAB3NzaC1yc2EAAAABIwAAAQEAsMqek5IpqFqI14hfmVuiZK1ZGX0RSUYjR9Wcdx1JrIgiHYA3HbCceqVw9KcwqOcjOWs+NH9qEgm9QHCFumueFpBqhlp04ClKur8PBGsAxjvLB1LQuQra6lw4icDBx7+8gu7grS2C5W7dZ5kG8jnrVTb4Dl9lcKPnbLfoRGCkfFPvEkr4aGfP4EsRFISxifm3b8sdVRga4gNFMedLCfTsYRApBnuZoGnExfCfuxOn5gZawwYEhXJCPkRXiWpudRYj29tiIac84pVc1A0OXBK2MqXPOCv6Gr7e2Z8mZVMJ+8ng9qcB6TmaUZ9IvRnsvwQWfetILycksZbzaQLQ+woRsQ==
swapfree => 1023.99 MB
swapfree_mb => 1023.99
swapsize => 1023.99 MB
swapsize_mb => 1023.99
timezone => BRT
uniqueid => 850ae981
uptime => 0:01 hours
uptime_days => 0
uptime_hours => 0
uptime_seconds => 113
virtual => vmware
```

`puppetdb` é uma ferramenta de agregação de informações sobre as máquinas, ou 
seja, ela armazena os relatórios após as máquinas executarem o puppet, é uma 
espécie de *splunk* de relatórios de automação do puppet.

O puppet em sua essência não garante a ordem de execução de acordo com a ordem
de declaração das classes.

```sh
# o argumento --noop testa a automação sem aplicar no host
puppet apply init.pp --noop
```

# Referências

- [Apostila de puppet PT-BR](https://github.com/instruct-br/apostila-puppet)
- [Puppet Labs GH](https://github.com/puppetlabs)
- [Puppet DB](https://github.com/puppetlabs/puppetdb) - [Docs](http://docs.puppetlabs.com/puppetdb)
- [Exemplo de automação com template](http://confluence.intranet.uol.com.br/confluence/display/IMP/httpd)
- Plus: [kickstart](https://www.vivaolinux.com.br/artigo/Instalacao-automatizada-de-servidores-com-kickstart)
- [Puppet 2.7 Docs](https://docs.puppet.com/puppet/2.7/reference/)
- [Puppet 2.7 Resources](https://docs.puppet.com/puppet/2.7/reference/type.html)
