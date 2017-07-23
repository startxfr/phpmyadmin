# Conf directory for container compat

if you place a config.inc.php file in this directory and he will be used 
if no config file is present in root directory

Useful for container based runtime who require to mount a volume to a directory (not a file)
especialy [Openshift Config Maps](https://docs.openshift.org/latest/dev_guide/configmaps.html)