semantic versioning
4.15.2

4 -> major  
15 -> minor  
2 -> patch  


- exact match: 4.15.2
- strict match only major: ^4.15.2
- strict match major and minor: ~4.15.2

package.json is the input  
package-lock.json is the output. It should be included in version control. It ensures the dependency tree is exactly the one we want.  

Update package:  
npm update namePkg, OR  
npm install namePkg (install the lastest version), OR  
npm install namePkg@4.15.2, OR  
npm install namePkg@latest

Remove a package:  
npm uninstall namePkg

See outdated packages
npm outdated
nmp outdated -g  

Global dependencies are: %appdata%\npm\node_modules

Cache:  
npm cache verify
npm cache clean --force
  