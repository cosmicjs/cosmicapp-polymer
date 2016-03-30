# Polymer & CosmicJS Blog

Creating list of blog posts using [Polymer](https://www.polymer-project.org/1.0/) & [CosmicJS](https://cosmicjs.com/).

CosmicJS is in private beta at the moment. Go [here](https://cosmicjs.com/signup) to sign up for a free account. You should be notified soon confirming your account has been created.

CosmicJS is "A Better Way to Manage Content".

![Blog Picture](https://s3-us-west-2.amazonaws.com/mandrewdarts-repos/polymer-cosmicjs.png)

## Run
```shell
npm install

npm start
```

If you have problems try running
```
bower install
```

## Configure

The `blog-title` and `post-list` elements are able to receive your CosmicJS bucket name as a property. The `post-list` element takes an additional property named `object-type` which is the object in your bucket you want to iterate over.

Notice: **I have an extra metafield with a key of "excerpt" added to my posts object.**

```html
<blog-title bucket="<your-bucket-name>"></blog-title>
<post-list bucket="<your-bucket-name>" object-type="<your-object-type>"></post-list>
```
