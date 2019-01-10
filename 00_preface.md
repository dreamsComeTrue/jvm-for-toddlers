It was always tough to me, remembering what various Java's JVM switches are used for. 

I've always struggled with carefully adjusting different parameters on the JVM, hoping, that any of them will improve overall performance of my app.

So, I've decided - the best way to learn internals of the JVM - will be look through its source code! 
I didn't find any exhaustive documentation over the web, so this will be my attempt to face this complex repository of JVM source.
In my ramblings, 

I will be operating on **OpenJDK v.11**, as it is the current one, and they get rid of additional dependencies, like
Nashorn scripting engine, or ancient CORBA.

I wish you (and me :)) a nice journey!
