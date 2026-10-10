# astro-firebase-mockblog
Quick small project to get familiarized with Astro and firebase

 [!NOTE] FireBase has been changed to Cloudflare Pages :) 

# Summary
Along the way, I've done

- Setup repo, test branch, first commit [10/10/2026]



# Notes
[10/11/2026]
- Whatev in src\pages directory can be accessed via URL.
- Frontmatter - meta info you define, Astro can use, and is not visible by default in browser.
- global.cs as the name sugges defines css site wide.



# High level steps

## Setting up env

### Managing node with conda

- Created conda env with even num versioned nodejs
```
$path> conda create -n myastroenv nodejs=24
```

![alt text](readme-assets/installingNode.png)

- Activated  ennv
```
$path> conda activate myastroenv
```

### Installed/Launched Astrojs

- Updated npm just to be safe :)
```
$path> npm install -g npm

$path> npm create astro@latest
```
![alt text](readme-assets/astrointializing.png)





