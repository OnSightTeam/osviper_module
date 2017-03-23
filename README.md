### General Information

Viper Module Template for [Generamba](https://github.com/rambler-digital-solutions/Generamba) code generator inspired on [Ramber Viper Controller templates](https://github.com/rambler-digital-solutions/generamba-catalog).

OnSight team use this viper template for generating modules on Viper architecture with UIViewController playing as a View.

### Creating Templates

- Open file “Rambafile” generated file after setup Generamba for project
- Add template to the #templates list: 
       - `- {name: osviper_module, git: 'https://bitbucket.org/onsightukraine/osviper_module’}`
- Run command:
       - `generamba template install`
- Check if new template was added to the list:
       - `generamba template list`
- Generate new module with new template:
      - `generamba gen RegisterModule osviper_module`