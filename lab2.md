# Lab 2

### Why it is important to choose a LICENSE?
Licensing lets developers of a software control the rights for other parties to distribute and use of it, as well as to protect their intellectual property. For example, in order to keep the **derivative software** to remain **free** (as in freedom), ones may place *copyleft license* on their software. This makes sure that the original piece of software **not end up being used by nonfree (without copyleft) software**, which can be used to preserve the ideology of free software. Otherwise, ones may use *permissive license*, which only requires that the developers of the original software being attributed in code or documentation, and a little more.

### Why they SHOULDN'T use a project that doesn't have an explicit license
Without license, a software is protected by copyright law, which prevent them from using, modifying, and distributing of the software. Since the developers have not yet grant permissions for others to have any right to use their software, it is *illegal (I may be wrong on this)* for anyone to do anything with it.

### Opinions on Failure to follow the Open System Model Section of Why the Web beat Gopher
I disagree with the claim. Considering that most of the succesful tech companies develop their own proprietary softwares, make huge load of money and still make general public better off. Failure of Gopher isn't likely in its desire to keep the design of important parts of the technology to itself, but rather its management ability to do so with its limited resources. It could have release some early version of the technology to build up momentum, hire more engineers, and sell more of additional services that couple with its early technology. Gopher failed strategically, but it has nothing to do with not being open to hacker community. In contrast, even if I would have been open to the community, there was no guarantee that I would be able to beat Web.

### Justify why SailfishOS is not open source
If SailfishOS was to be open source, by the definition, any other company would be able to modify, use, and charge for the deviated software developed on top of the original SailfishOS. Jolla (owner of SailfishOS) may want to reserve its right to be the only party to monetize from the OS. Therefore, it did not license SailfaishOS as open source.

### GPL vs LGPL vs Apache/BSD
- GPL is a **copyleft** license, which means all the derivative work must be distributed under them same license, which grants the end users permissions to run, study, share and modify the software. The GPL provides most benefit for common good.
- The LGPL is similar to GPL, but without the copyleft. It is used mainly in libraries, as the softwares that use it do not have to release under the same LGPL, except ones that link the library statically. Such software must allow end users to make changes via source code as well. The LGPL provides a good balance of benefits for developers, for companies, as they can use the licensed softwares/libraries in their proprietary softwares, and for the common good, as it still requires the derivative work to be open for reverse-engineering.
- Apache/BSD licenses are very permissive. In summary, anyone can do almost anything with the softwares under such licenses. Therefore they are great for developers and companies as they also provide patent protections, but do not offer much to public good comparing to other licenses.

### Project
I will be working on a web application that supports functionalities similarly to the [Knowledge Explorer](https://github.com/smiled0g/knowledge-explorer). The Knowledge Explorer project has served as a tool for building graph of information from particular domains using data from [DBPedia](http://wiki.dbpedia.org/), for researchers in the department of Cognitive Science at RPI. The project is still actively used, but it is inefficient and requires complicated installation. The new project would be to improve performance and allow users to create and save data right on the website. It may as well allow the users to share and collaborate on building the database. It will be released under [MIT License](https://opensource.org/licenses/MIT).

### Licenses from observatory

Website | License Present | License
---------|:----------|:-------
https://github.com/wtg/shuttle_tracking_2 | Yes | MIT License https://en.wikipedia.org/wiki/MIT_License
https://github.com/FullScreenShenanigans/FullScreenPokemon | Yes | MIT License (Incomplete, need Copyright statement)
https://github.com/copperwater/yacs | Yes | MIT License
https://github.com/Polaritech/OLD.Slick | Yes | MIT License
https://github.com/Submitty/Submitty | Yes | BSD "3-Clause" License https://en.wikipedia.org/wiki/BSD_licenses

