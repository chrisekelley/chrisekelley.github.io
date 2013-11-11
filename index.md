---
layout: page
title: Software Projects
tagline: my projects hosted here and elsewhere
---
{% include JB/setup %}

## Olutindo
### Making data available offline

#### Nov. 11, 2013

<table>
  <tr>
    <td>
    <a name="olutindo" style="color:#000; border-bottom:0px">Olutindo</a> is a webapp for <a href="projects/2012/01/16/olutindo">managing citizen complaints in Uganda</a>. It is the html5 companion to the
    <a href='https://github.com/chrisekelley/olutindo-app'>Olutindo-app</a> Android application, which uses
    Phonegap/Cordova 3.x. Olutindo uses <a href='http://chrisekelley.github.io/coconut/'>Coconut</a> for most of its
    front-end form rendering, <a href='http://backbonejs.org'>backbone.js</a> for MVC, <a href='http://pouchdb.com/'>pouchdb</a>
    for browser-based data store and replication, and <a href='http://couchdb.apache.org/'>CouchDB</a> for the master data store.
    <br/>
    <br/>
    Slides for <a href="http://kinotel.com/barcelonajs-pouchdb-talk-12nov2013/">Using PouchDB for PhoneGap/Cordova apps</a>
    that features technical aspects of Olutindo.
    <br/>
    <br/>
    Github:
    <ul style="padding-left: 2em">
    <li><a href="https://github.com/chrisekelley/olutindo">Olutindo html5 version</a></li>
    <li><a href="https://github.com/chrisekelley/olutindo-app">Olutindo Android version</a></li>
    </ul>
    </td>
    <td>
    <img alt='Screenshot of Olutindo' src='images/olutindoAppHome50.png' />
    </td>
  </tr>
</table>

## AlloChrome

### WebGL FTW (eventually)

#### May 28, 2013

<table>
<tr>
<td>
<img alt='Screenshot of AlloChrome browser and url chooser' src='images/allochrome50.png' />
</td>
<td>
<p><a href="http://en.wikipedia.org/wiki/WebGL">WebGL</a> is a Javascript API for creating awesome 3D graphics for games and other apps.
Unfortunately (circa 2013) it is not available to developers who wish to create html5 apps using Phonegap/Cordova.
I built upon <a href='https://github.com/pwnall'>Victor Costan</a>'s work on <a href='https://github.com/pwnall/chromeview'>ChromeView</a>
by creating an app that tests the performance of 2D and 3D Javascript frameworks - <a href='http://jonobr1.github.io/two.js/'>two.js</a>,
<a href='http://threejs.org/'>three.js</a>, and <a href='https://github.com/GoodBoyDigital/pixi.js'>pixi</a> -  in ChromeView.
A future goal would be to include WebGL tests once that API is available in ChromeView.
</p>
<p>Github: <a href='https://github.com/chrisekelley/AlloChrome'>AlloChrome</a>
</p>
</td>
</tr>
</table>

## voxeljs projects

### Browser-based Games

#### Summer 2013

<table>
<tr>
<td>
I have worked on a few projects supporting <a href="voxeljs.com">VoxelJS</a>, which enables the creation of  3D voxel
games like Minecraft in the browser:
<ul style="padding-left: 2em">
  <li><a href="https://github.com/chrisekelley/voxel-label">Voxel-label</a> is a <a href='http://voxeljs.com/#modules'>voxeljs module</a> that implements
  <a href='http://japhr.blogspot.com.es/2013/03/fun-with-threejs-camera-orientation.html'>LabelPlugin</a>, a three.js plugin
  that adds labels to your game players (avatars). It can work in single-player mode as well as with
  <a href='https://github.com/maxogden/voxel-client'>voxel-client</a> for labelling all avatars in a multiplayer game.
  </li>
  <li>I did some commits on <a href='https://github.com/maxogden/voxel-client'>voxel-client</a>, which enables an app
  based on voxel-engine to be a client for <a href="https://github.com/maxogden/voxel-server">voxel-server</a> </li>
  <li><a href='https://github.com/chrisekelley/voxel-app-server'>voxel-app-server</a> is an extended implementation of
  <a href='http://github.com/maxogden/voxel-server'>voxel server</a>, which is a multiplayer server for
  <a href='http://github.com/maxogden/voxel-engine'>voxel-engine</a>. voxel-app-server implements a voxeljs game using
  express (specifically express3), with user registration and authentication via <a href='https://github.com/bnoguchi/everyauth/tree/express3'>everyauth</a></li>
</ul>
</td>
<td style="vertical-align:middle">
<img alt='Screenshot of minecraft-like players with labels' src='images/voxel-label-400.png' />
    Github:
    <ul style="padding-left: 2em">
    <li><a href="https://github.com/chrisekelley/voxel-label">voxel-label</a></li>
    <li><a href='https://github.com/maxogden/voxel-client'>voxel-client</a></li>
    <li><a href='https://github.com/chrisekelley/voxel-app-server'>voxel-app-server</a></li>
    </ul>
</td>
</tr>
</table>

## Andromeda

### Managing Android Deployments

#### Feb. 27, 2013
<table>
<tr>
<td><img alt='Screenshot of record listing' src='images/andromeda_50_crop.png' /></td>
<td style="vertical-align:middle">
<p><a href='https://github.com/chrisekelley/Andromeda'>Andromeda</a> demonstrates how to manage the user registration
and management process using Syncpoint-Android. It is a demo of <a href='https://github.com/couchbaselabs/TouchDB-Android'>TouchDB-Android</a>
and <a href='https://github.com/couchbaselabs/Syncpoint-Android'>Syncpoint-Android</a> using
<a href='http://incubator.apache.org/projects/callback.html'>Apache Cordova (formerly PhoneGap)</a>,
<a href='http://couchapp.org'>Couchapp</a>, <a href='https://github.com/addyosmani/todomvc'>TodoMVC</a>, and
<a href='http://actionbarsherlock.com/'>ActionBarSherlock</a>.
It is an extension of <a href='https://github.com/chrisekelley/Android-TouchDB-Cordova#android-couchbase-callback'>Android-TouchDB-Cordova</a>,
which is a demonstration of the <a href='https://github.com/addyosmani/todomvc/tree/master/dependency-examples/backbone_require'>TodoMVC backbone-require</a> app,
which has been modified to work as a <a href='https://github.com/tbranyen/backbone-boilerplate'>Backbone boilerplate</a> project.
It is based upon <a href='https://github.com/couchbaselabs/Android-Couchbase-Callback'>Android-Couchbase-Callback</a>.
</p>
<p>Github: <a href='https://github.com/chrisekelley/Andromeda'>Andromeda</a></p>
</td>
</tr>
</table>

## Coconut

### Form Generation

#### 2011 - 2013

<table>
<tr>
<td><p><a href='http://chrisekelley.github.io/coconut/'>Coconut</a> renders JSON defined forms in a browser and then
saves the results to CouchDB. Coconut uses CouchDB for data storage and synchronization,
<a href='http://documentcloud.github.com/backbone'>Backbone.js</a> for MVC,
<a href='https://github.com/janmonschke/backbone-couchdb'>backbone-couchdb</a> to connect backbone to CouchDB, and
<a href='http://mbostock.github.com/d3/'>D3</a> for charts.</p>
    <p>Coconut can be run on a computer or installed on a mobile phone or tablet. Some examples:
    <ul>
    <li><a href="#olutindo">Olutindo</a> uses Coconut to render forms.</li>
    <li><a href='https://github.com/vetula/Android-Coconut-MobileFuton'>Android-Coconut-MobileFuton</a> for Android 10.1&#8221; tablets. </li>
    <li><a href='https://github.com/vetula/Android-Tims-MobileFuton'>Android-Tims-MobileFuton</a> for Android smart phones.</li>
    </ul>
    </p>
</td>
<td style="text-align:center"><img alt='Screenshot of record listing' src='images/coconut_record_listing.png' />
<br/>
<br/>
Github: <a href="https://github.com/chrisekelley/coconut">coconut</a></td>
</tr>
</table>

## My Repositories and Other Work

- [Github](https://github.com/chrisekelley?tab=repositories)
- [Zcore](/projects/2011/05/02/zcore)

## Posts

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>


