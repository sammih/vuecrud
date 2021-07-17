## Vue Crud

We need to install vue to our laravel app
- npm run vue *This commad will get the stable vue version*
- Now that we have vue js installed to our laravel app, we need to do some tweaks;
> open webpack file located in the root directory of our app and add .vue():
>> mix.js('resources/js/app.js', 'public/js').vue() .postCss('resources/css/app.css', 'public/css', [ // ]);
- npm run dev