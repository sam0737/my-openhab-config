The openHAB 2 configuration for my home

Please refer to my setup: https://medium.com/@it9gamelog/c722d2e816f6

# Installation of Add-ons #

Some of my setup requires the Expire add-ons.
Here is how to install it to a openHAB 2 setup

 1. Download the jar file from [here](https://openhab.ci.cloudbees.com/job/openHAB1-Addons/lastSuccessfulBuild/artifact/bundles/binding/org.openhab.binding.expire/target/)
 1. Put into `/usr/share/openhab2/addons` (for openHABian)
 1. Enter openHAB console by `openhab-cli console`, the password is `habopen`
 1. Check if the expire binding is active `bundle:list | grep -i expire`
 1. If it is not, try to start it again `bundle:start org.openhab.binding.expire`

# Folder Structure #

The `/etc` folder corresponding to the `/etc/openhab2` (for openHABian) folder. Applies what you see fit.
