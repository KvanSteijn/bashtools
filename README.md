# Bashtools
Bash scripts for creating PHP-FPM pools, Nginx configs and databases

# Installation
Clone this repository 
```
git clone git@github.com:KvanSteijn/bashtools.git
cd bashtools
```

Chmod the bash files
```
chmod u+x addwebsite addwebsiteconfig adddatabase enablewebsite disablewebsite
```

# Create website
Run this command for creating complete website (website directory, PHP-FPM pool, Nginx config and database).
```
./addwebsite WEBSITENAME EXTENSION WEBSITETYPE
```
## Example
Create default website.
```
./addwebsite example com
```

Create wordpress website.
```
./addwebsite example com wordpress
```
