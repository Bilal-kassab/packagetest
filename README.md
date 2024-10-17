## run this command:
This command is used to install the package
> #### composer require interreposerv/inreser
<br />

## How to use:

### First, make an Interface: ###
> #### php artisan make:interface YourInterfaceName
<br />


### Second, make a Repository ###
make sure that u pass the previous interface name  
> #### php artisan make:repository YourRepositoryName --interface=YourInterfaceName
<br />

### Third, make a Service ###
> #### php artisan make:service YourServiceName
<br />