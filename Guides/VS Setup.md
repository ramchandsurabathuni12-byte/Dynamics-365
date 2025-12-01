By cloning the Git repo to local, you get the model folder to the local repo.
Now, you need to create a link into packages local folder by using the following command.

mklink /d NSI C:\Users\Admin0b1cc5c3c0\source\repos\FDD-002-Report\Metadata\NSI


After this, you will be able to create new objects into the model and see the changes in GitChanges to check-in.


1. Goto _> Local Packages folder : K:\AosService\PackagesLocalDirectory
1. Open cmd
1. cd/
1. K:
1. cd K:\AosService\PackagesLocalDirectory
1. mklink /d SRC C:\Users\Admin0b1cc5c3c0\source\repos\RC\Dynamics-365\SRC

Now you can see the following output

symbolic link created for SRC <<===>> C:\Users\Admin0b1cc5c3c0\source\repos\RC\Dynamics-365\SRC

Now Refresh models from 

Extensions->Dynamics 365->Model management->Refresh models

