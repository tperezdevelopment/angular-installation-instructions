# Installation an Angular Specific Version

<hr>
<h2> Before Installation </h2>
<ol>
    <li>
      <h3>Install nvm for Windows to use multiple nodejs versions</h3>
      <ol>
        <li>Download from: <a href="https://github.com/coreybutler/nvm-windows/releases" target="_blank">NVM GitHub</a></li>
        <li>For installing and running Node.js version 18
          <ol>
            <li>Run: <code>nvm install 18</code></li>
            <li>Run: <code>nvm use 18</code></li>
          </ol>
        </li>
        </ol>
      <li>
      <h3>Cleaning Angular Global Version Already Installed</h3>
      <ol>
        <li>Run: <code>npm uninstall -g @angular/cli</code></li>
        <li>Run: <code>npm cache clean --force</code></li>
      </ol>
    </li>
</ol>
<hr>
<h2>Using Angular Version 13.3.0 as the specific version</h2>
<h3>As a global installation</h3>
  <ol>
         <li>Run: <code>npm install -g @angular/cli@13.3.0</code></li>
        <li>Run: <code>ng new older-version-app</code></li> 
    </ol>
    <h3>As a local installation</h3>
  <ol>
         <li>cd to the folder where you will install the local Angular version</li>   
         <li>Run: <code>npm install @angular/cli@13.3.0</code></li>
        <li>Run: <code>npx ng new older-version-app</code></li> 
    </ol>
