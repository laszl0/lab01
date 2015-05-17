
When runing the command verify and there is an error similar to this:
"C:\Program " could not be found.
Just go to the following location:

C:\Users\Razuro-TP-i5\AppData\Roaming\npm\node_modules\how-to-npm\problems

And edit your problem file, find 
npm = which.sync('npm')
and replace it with npm='npm'
That should solve it.