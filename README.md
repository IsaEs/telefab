# Telefab

Telecontact.me floating action button plugin for websites.

## Usage

Available settings for your telefab.

- telefab-name -- Name of your formId
- telefab-id : Uniqe teleform HASH_ID for your form
- data-header: Header for FAB

// TODO customization attributes

- data-explanation: Header explanation
- data-main-color: Color of your header
- data-button-color: Send Button color for

```js
//Template
<script
  async src="https://www.telecontact.me/telefab.js"
  telefab-name={{NAME}}
  telefab-id={{HASH_ID}}
  data-header={{HEADER}}
/>

// Example Usage
<script
  async src="https://www.telecontact.me/telefab.js"
  telefab-name="TestButton"
  telefab-id="W-lx1JJLMKb6"
  data-header="👋 Telecontact.me"
/>
```

## Default

![telefab](assets/telefab.gif "Telefab Action Button")
