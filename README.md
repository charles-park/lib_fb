# lib_ui (2025.06.12, lib_fbui로 부터 fb부분만 분리)
Framebuffer only version (1bpp 추가, lib_fbui의 1bpp추가 시점으로 분리. 일반 Framebuffer에 사용하기 위함).

```
root@server:~/lib_fb# ./lib_fb -h

Usage: ./lib_fb [-DrgbxywhfntscCi]
  -D --device    device to use (default /dev/fb0)
  -R --rotate    fb rotate display (0, 90, 180, 270. default = 0)
  -r --red       pixel red hex value.(default = 0)
  -g --green     pixel green hex value.(default = 0)
  -b --blue      pixel blue hex value.(default = 0)
  -x --x_pos     framebuffer memory x position.(default = 0)
  -y --y_pos     framebuffer memory y position.(default = 0)
  -w --width     reference width for drawing.
  -h --height    reference height for drawing.
  -f --fill      drawing fill box.(default empty box)
  -n --thickness drawing line thickness.(default = 1)
  -t --text      drawing text string.(default str = "text"
  -s --scale     scale of text.
  -c --color     background rgb(hex) color.(ARGB)
  -C --clear     clear framebuffer(r = g = b = 0)
  -i --info      framebuffer info display.
  -F --font      Hangul font select
                 0 MYEONGJO
                 1 HANBOOT
                 2 HANGODIC
                 3 HANPIL
                 4 HANSOFT
  Useage : ./lib_fb -s 2 -F 2
```
