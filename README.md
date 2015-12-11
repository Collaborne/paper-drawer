paper-drawer [![Bower version](https://badge.fury.io/bo/paper-drawer.svg)](http://badge.fury.io/bo/paper-drawer)
=========

`paper-drawer` provides components to build a material design [drawer](https://www.google.com/design/spec/patterns/navigation-drawer.html). The web component is built with [Polymer 1.x](https://www.polymer-project.org).

The components are designed to be used in combination with [`paper-drawer-panel`](https://github.com/PolymerElements/paper-drawer-panel).

![Screenshot](/doc/screenshot.png "Screenshot")


## Usage

`bower install paper-drawer`

```html
<paper-drawer>
  <paper-drawer-title photo="face.png" name="Jonathan Lee" email="heyfromjonathan@gmail.com"></paper-drawer-title>
  
  <paper-drawer-subheader>Items with icon</paper-drawer-subheader>
  <paper-drawer-icon-item icon="icons:mail">All mail</paper-drawer-icon-item>
  <paper-drawer-icon-item icon="icons:delete">Trash</paper-drawer-icon-item>
  <paper-drawer-icon-item icon="icons:error">Spam</paper-drawer-icon-item>
  
  <paper-drawer-divider></paper-drawer-divider>
  
  <paper-drawer-subheader>Items without icon</paper-drawer-subheader>
  <paper-drawer-item>All mail</paper-drawer-item>
  <paper-drawer-item>Trash</paper-drawer-item>
  <paper-drawer-item>Spam</paper-drawer-item>
</paper-drawer>
```


## Properties & styles

These properties are available for `paper-drawer-title`:

Property  | Type   | Description
--------- | ------ | --------------
**photo** | String | URL to the photo of the person
**name**  | String | Name of the person
**email** | String | Email of the person

Style                                 | Description
------------------------------------- | ------------
--paper-drawer-title-background-color | Background color of the title area
--paper-drawer-title-color            | Font color of the name and email
--paper-drawer-title                  | Mix-in applied to the title area

These properties are available for `paper-drawer-icon-item`:

Property | Type    | Description
-------- | ------- | ----------------------------
**icon** | String  | Icon that is shown next to the content


## License

    This software is licensed under the Apache 2 license, quoted below.

    Copyright 2011-2015 Collaborne B.V. <http://github.com/Collaborne/>

    Licensed under the Apache License, Version 2.0 (the "License"); you may not
    use this file except in compliance with the License. You may obtain a copy of
    the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS, WITHOUT
    WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the
    License for the specific language governing permissions and limitations under
    the License.
    