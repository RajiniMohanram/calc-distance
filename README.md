<h1>Install AGM core </h1>
<code>npm install @agm/core --save</code>
<h3>If it gives ERESOLVE unable to resolve dependency tree error, try</h3>
<div><code>npm install --save --legacy-peer-deps</code></div>
<div><code>npm config set legacy-peer-deps true</code></div>
<div><code>npm install @agm/core --save</code></div>

<h1>Configure app.module.ts</h1>
<code>import { AgmCoreModule } from '@agm/core';</code>
<pre>
  @NgModule({
  imports: [
    BrowserModule,
    AgmCoreModule.forRoot({
      apiKey: ''
    })
  ],
</pre>

