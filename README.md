#HLS Convertor
powered by lumen

#installation

You need to install FFmpeg on your machine (if you are working on PC) else you need to install FFmpeg on your serve

Installing FFmpeg in Ubuntu:
<pre>sudo apt-get install ffmpeg</pre>

On Mac
<pre>brew install ffmpeg</pre>

Create storage link
<pre>ln -s php-hls-convertor/storage/app  php-hls-convertor/public/storage</pre>

Install composer packages
<pre>composer install</pre>

Install npm packages 
<pre>npm install</pre>

npm build dev
<pre>npm run dev</pre>

npm build production
<pre>npm run prod</pre>

to start converter job
<pre>php artisan queue:work</pre>
