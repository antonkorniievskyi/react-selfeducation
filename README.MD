<h1>React template</h1>
<hr>
<h2>Technologies Used</h2>
<hr>
<ul>
  <li>React</li>
</ul>
<ul>
  <li>TypeScript</li>
</ul>
<ul>
  <li>Eslit</li>
</ul>

<h2>Setup</h2>
<hr>
<p>Project requirements: node v16.13.1, yarn v1.22.19
<p>
<h5>Steps</h5>
<ul>
  <li>create an <code>.env</code> file in the application's root directory</li>
</ul>
<ul>
  <li>poppulate <code>.env</code> file according to <code>.env.sample</code></li>
</ul>
<ul>
  <li>run <code>yarn</code> in the root of project directory to install all the dependencies</li>
</ul>
<h2>Usage</h2>
<hr>
<ul>
  <li>Deployment:
    <ul>
      <li>run <code>yarn build</code> to create optimized production build</li>
      <li>serve <code>dist</code> foler</li>
    </ul>
  </li>
  <li>Development:
    <ul>
      <li>run <code>yarn dev</code> to start app in development mode</li>
    </ul>
  </li>
  <li>Preview
    <ul>
      <li>run <code>yarn preview</code> to locally check you production build</li>
    </ul>
  </li>
</ul>

<h5>Code Examples</h5>
<ul>
  <li>Check whether the app is running in production {boolean}</li>
</ul>
<p>
  <code>const isProduction = import.meta.env.PROD</code>
</p>
<ul>
  <li>Check whether the app is running in development {boolean} (always the opposite of
    <code>import.meta.env.PROD</code>)</li>
</ul>
<p><code>const idDevMode = import.meta.env.DEV</code></p>
<ul>
  <li>Using custom environment variables</li>
</ul>
<p><code>const someKey = import.meta.env.VITE_SOME_KEY;</code></p>
<h2>Features that can be added</h2>
<hr>
<ul>
  <li>Form and Validations:
    <ul>
      <li>React Hook Form [https://react-hook-form.com]</li>
      <li>Yup [https://github.com/jquense/yup]</li>
    </ul>
  </li>
</ul>
<ul>
  <li>State management:
    <ul>
      <li>Redux [https://react-redux.js.org]</li>
      <li>Redux-Saga [https://redux-saga.js.org]</li>
      <li>Redux Toolkit [https://redux-toolkit.js.org]</li>
    </ul>
  </li>
</ul>