<p align="center"><img src="./art/dropzone.png" width="80%" alt="Livewire Dropzone"></p>

## ✨ Introduction
This repository is fork of [dasundev/livewire-dropzone](https://github.com/dasundev/livewire-dropzone) repository for iohttp projects to achieve high stability on minor changes.

## 📦 Installation
You can install the package via Composer:
```bash
composer require iohttp/livewire-dropzone
```

To install the styles package, use the following command:
```bash
npm i @dasundev/livewire-dropzone-styles
```

Import styles to your project
```scss
/* resources/css/app.css */

@import "@dasundev/livewire-dropzone-styles";
```

## 🎬 Showcase
Now you can use the dropzone component as you like.
```html
<livewire:dropzone
        wire:model="banners"
        :rules="['image','mimes:png,jpeg','max:10420']"
        :multiple="true" />
```

## 🎨 Tailor UI
The dropzone component is entirely customizable. Just publish the view file and make it your own.
```bash
php artisan vendor:publish --tag=livewire-dropzone-views
```

## 📝 Author Blog Post
I made a blog post about using the Livewire dropzone to store files permanently. It's perfect for people new to Laravel. You can read the blog post [here](https://www.dasun.dev/blog/how-to-use-livewire-dropzone).

