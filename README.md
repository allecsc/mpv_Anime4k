# mpv_Anime4k

Simple MPV build for watching anime that I put together for my personal use. 

Uses **Anime4k shaders** (https://github.com/bloc97/Anime4K) for **real-time "upscaling"**. Works **great with anime**, not so much with anything else, I wouldn't recommend using it with anything else.

![SVP](https://github.com/user-attachments/assets/15b72851-f7e7-428d-8fc3-203bd0613fe7)

I've managed to find and add some old version of SVP so it can create extra frames **automatically** and **turn any video into 60 FPS**. Basically, I've merged my mpv with this one from reddit: https://www.reddit.com/r/mpv/comments/kqdvgv/mpvsvp_motion_interpolation_in_a_complete_package/ , you can read there more about it, and I might have updated it to some more recent version, if my memory serves me right.

There's options for 48 FPS, and 120 FPS (this is EXPERIMENTAL and NOT RECOMMENDED). It mostly works, depends a lot on your hardware as well. Rarely, it might desync audio and video, you can fix it by skipping forwards/backwards. SVP is the only thing prone to crashes and other errors if used on videos other than anime/cartoons. 

![Howtowatchonlineanime60FPS](https://github.com/user-attachments/assets/e4c1d25e-57e2-4a86-ad77-fbf08be2f4de)

Also, you can **copy+paste** URLs and HLS streams from your favorite websites **directly into the player**, without downloading anything. Autoprofile is set to apply shaders and 60 FPS to any link played since I use it only for watching anime. 
You need this extension to find HLS streams: https://chromewebstore.google.com/detail/the-stream-detector/iakkmkmhhckcmoiibcfjnooibphlobak

![history](https://github.com/user-attachments/assets/00c4f774-f9e3-4280-8d3d-16c9261bd2b1)

Has a **playlist, history and recents lists** with search, it **saves video position and resumes** from there. 
There's other features I don't really use that often, but I played around a lot when putting it all together. I believe I've implemented everything to show up in the menu, but **I highly recommend to check the key bindings list** for everything there is. 

This project was made some time ago so I don't remember all the little things. It mostly works, I use it everyday, it's my main video player for everything. I don't plan on working on it anymore, but feel free to improve upon it and let me know if anyone's interested.

There's 2 versions: 

- mpv      - uses Anime4k HQ shaders - requires powerful high-end PC
- **mpvLite**  - uses Anime4k Fast shaders - should work on any configuration and is the most optimized and up-to-date version - **RECOMMENDED**

I use mpvLite daily on my laptop which serves as a media center hooked up to the TV. For references, laptop is a Lenovo Legion Y7000 - i5-9300H - GTX 1650.

