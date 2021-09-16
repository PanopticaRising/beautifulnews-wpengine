This is a simple HTML wrapper around the BeautifulNews RSS Feed. It currently uses a development proxy to bypass Feedburner's CORS issue. Because of that, it is not suitable for long-term use and is not published to the WP Engine Workshop.

To run this locally:
1. Go to [CORS Anywhere](https://cors-anywhere.herokuapp.com/) and request development access to the proxy server.
2. Clone thie repository
3. Run `npm install`
4. Launch Wallpaper Engine
5. Navigate to "Create A New Wallpaper"
6. Drag and drop the `index.html` file from this repository into Wallpaper Engine.
7. (Optional) The following "User Properties" can be added:
  1. Color: `backgroundcolor`
  2. Slider: `duration`
  3. Checkbox: `random`