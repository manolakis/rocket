# Launch Theme >> Inline Notification ||20

Notification are web components that bring in some styles.

To use them in Markdown you need to write the html tag and have it separated by an empty line.

```js script
import '@d4kmor/launch/inline-notification/inline-notification.js';
```

First you need to import the script

````
```js script
import '@d4kmor/launch/inline-notification/inline-notification.js';
```
````

## Tip

<inline-notification type="tip">

I am a tip

</inline-notification>

**Usage**

```md
<inline-notification type="tip">

I am a tip

</inline-notification>
```

## Modify the title

To override the title you can provide a property success.

<inline-notification type="tip" title="success">

I am a success message

</inline-notification>

**Usage**

```md
<inline-notification type="tip" title="success">

I am a success message

</inline-notification>
```

## Warning

<inline-notification type="warning">

I am a warning

</inline-notification>

**Usage**

```md
<inline-notification type="warning">

I am a warning

</inline-notification>
```

## Danger

<inline-notification type="danger">

I am a dangerous message

</inline-notification>

**Usage**

```md
<inline-notification type="danger">

I am a dangerous message

</inline-notification>
```
