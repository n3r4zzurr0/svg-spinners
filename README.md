# <img src="./preview/icon-48.gif" valign="middle">&nbsp;&nbsp;SVG Spinners (CSS & SMIL)

All spinners are displayed inside a 24 x 24 dp view box. The main content rests inside the live area of 22 dp with a padding of 1dp.

**Few points to consider:**

1. SMIL animations (both inline and referenced via an `img` tag) won't start playing until the page has completely loaded whereas CSS animations will start playing while the page is loading.
2. In webkit based browsers, both SMIL and CSS animations, when referenced via an `img` tag, produce an [unusual behavior](https://github.com/n3r4zzurr0/svg-spinners/issues/2) on page zoom levels other than 100%. Using them inline seems completely fine and consistent across browsers.

<br />

## Preview

<h3>Rings</h3><table><tr><th>Preview</th><th>CSS (Size in bytes)</th><th>SMIL (Size in bytes)</th></tr><tr><td><picture><source media="(prefers-color-scheme: dark)" srcset="./preview/90-ring-white-36.svg"><img src="./preview/90-ring-black-36.svg"></picture></td><td><a href="./svg-css/90-ring.svg">CSS</a> (428)</td><td><a href="./svg-smil/90-ring.svg">SMIL</a> (384)</td></tr><tr><td><picture><source media="(prefers-color-scheme: dark)" srcset="./preview/90-ring-with-bg-white-36.svg"><img src="./preview/90-ring-with-bg-black-36.svg"></picture></td><td><a href="./svg-css/90-ring-with-bg.svg">CSS</a> (531)</td><td><a href="./svg-smil/90-ring-with-bg.svg">SMIL</a> (487)</td></tr><tr><td><picture><source media="(prefers-color-scheme: dark)" srcset="./preview/180-ring-white-36.svg"><img src="./preview/180-ring-black-36.svg"></picture></td><td><a href="./svg-css/180-ring.svg">CSS</a> (434)</td><td><a href="./svg-smil/180-ring.svg">SMIL</a> (390)</td></tr><tr><td><picture><source media="(prefers-color-scheme: dark)" srcset="./preview/180-ring-with-bg-white-36.svg"><img src="./preview/180-ring-with-bg-black-36.svg"></picture></td><td><a href="./svg-css/180-ring-with-bg.svg">CSS</a> (537)</td><td><a href="./svg-smil/180-ring-with-bg.svg">SMIL</a> (493)</td></tr><tr><td><picture><source media="(prefers-color-scheme: dark)" srcset="./preview/270-ring-white-36.svg"><img src="./preview/270-ring-black-36.svg"></picture></td><td><a href="./svg-css/270-ring.svg">CSS</a> (483)</td><td><a href="./svg-smil/270-ring.svg">SMIL</a> (439)</td></tr><tr><td><picture><source media="(prefers-color-scheme: dark)" srcset="./preview/270-ring-with-bg-white-36.svg"><img src="./preview/270-ring-with-bg-black-36.svg"></picture></td><td><a href="./svg-css/270-ring-with-bg.svg">CSS</a> (586)</td><td><a href="./svg-smil/270-ring-with-bg.svg">SMIL</a> (542)</td></tr><tr><td><picture><source media="(prefers-color-scheme: dark)" srcset="./preview/ring-resize-white-36.svg"><img src="./preview/ring-resize-black-36.svg"></picture></td><td><a href="./svg-css/ring-resize.svg">CSS</a> (620)</td><td><a href="./svg-smil/ring-resize.svg">SMIL</a> (739)</td></tr></table><br /><h3>Dots</h3><table><tr><th>Preview</th><th>CSS (Size in bytes)</th><th>SMIL (Size in bytes)</th></tr><tr><td><picture><source media="(prefers-color-scheme: dark)" srcset="./preview/3-dots-bounce-white-36.svg"><img src="./preview/3-dots-bounce-black-36.svg"></picture></td><td><a href="./svg-css/3-dots-bounce.svg">CSS</a> (635)</td><td><a href="./svg-smil/3-dots-bounce.svg">SMIL</a> (686)</td></tr><tr><td><picture><source media="(prefers-color-scheme: dark)" srcset="./preview/3-dots-fade-white-36.svg"><img src="./preview/3-dots-fade-black-36.svg"></picture></td><td><a href="./svg-css/3-dots-fade.svg">CSS</a> (482)</td><td><a href="./svg-smil/3-dots-fade.svg">SMIL</a> (599)</td></tr><tr><td><picture><source media="(prefers-color-scheme: dark)" srcset="./preview/3-dots-move-white-36.svg"><img src="./preview/3-dots-move-black-36.svg"></picture></td><td><a href="./svg-css/3-dots-move.svg">CSS</a> (631)</td><td><a href="./svg-smil/3-dots-move.svg">SMIL</a> (2973)</td></tr><tr><td><picture><source media="(prefers-color-scheme: dark)" srcset="./preview/3-dots-rotate-white-36.svg"><img src="./preview/3-dots-rotate-black-36.svg"></picture></td><td><a href="./svg-css/3-dots-rotate.svg">CSS</a> (409)</td><td><a href="./svg-smil/3-dots-rotate.svg">SMIL</a> (375)</td></tr><tr><td><picture><source media="(prefers-color-scheme: dark)" srcset="./preview/3-dots-scale-white-36.svg"><img src="./preview/3-dots-scale-black-36.svg"></picture></td><td><a href="./svg-css/3-dots-scale.svg">CSS</a> (471)</td><td><a href="./svg-smil/3-dots-scale.svg">SMIL</a> (503)</td></tr><tr><td><picture><source media="(prefers-color-scheme: dark)" srcset="./preview/3-dots-scale-middle-white-36.svg"><img src="./preview/3-dots-scale-middle-black-36.svg"></picture></td><td><a href="./svg-css/3-dots-scale-middle.svg">CSS</a> (422)</td><td><a href="./svg-smil/3-dots-scale-middle.svg">SMIL</a> (459)</td></tr><tr><td><picture><source media="(prefers-color-scheme: dark)" srcset="./preview/6-dots-rotate-white-36.svg"><img src="./preview/6-dots-rotate-black-36.svg"></picture></td><td><a href="./svg-css/6-dots-rotate.svg">CSS</a> (948)</td><td><a href="./svg-smil/6-dots-rotate.svg">SMIL</a> (692)</td></tr><tr><td><picture><source media="(prefers-color-scheme: dark)" srcset="./preview/6-dots-scale-white-36.svg"><img src="./preview/6-dots-scale-black-36.svg"></picture></td><td><a href="./svg-css/6-dots-scale.svg">CSS</a> (1494)</td><td><a href="./svg-smil/6-dots-scale.svg">SMIL</a> (2875)</td></tr><tr><td><picture><source media="(prefers-color-scheme: dark)" srcset="./preview/6-dots-scale-middle-white-36.svg"><img src="./preview/6-dots-scale-middle-black-36.svg"></picture></td><td><a href="./svg-css/6-dots-scale-middle.svg">CSS</a> (1504)</td><td><a href="./svg-smil/6-dots-scale-middle.svg">SMIL</a> (2587)</td></tr><tr><td><picture><source media="(prefers-color-scheme: dark)" srcset="./preview/8-dots-rotate-white-36.svg"><img src="./preview/8-dots-rotate-black-36.svg"></picture></td><td><a href="./svg-css/8-dots-rotate.svg">CSS</a> (535)</td><td><a href="./svg-smil/8-dots-rotate.svg">SMIL</a> (484)</td></tr><tr><td><picture><source media="(prefers-color-scheme: dark)" srcset="./preview/12-dots-scale-rotate-white-36.svg"><img src="./preview/12-dots-scale-rotate-black-36.svg"></picture></td><td><a href="./svg-css/12-dots-scale-rotate.svg">CSS</a> (1693)</td><td><a href="./svg-smil/12-dots-scale-rotate.svg">SMIL</a> (2714)</td></tr><tr><td><picture><source media="(prefers-color-scheme: dark)" srcset="./preview/dot-revolve-white-36.svg"><img src="./preview/dot-revolve-black-36.svg"></picture></td><td><a href="./svg-css/dot-revolve.svg">CSS</a> (399)</td><td><a href="./svg-smil/dot-revolve.svg">SMIL</a> (357)</td></tr></table><br /><h3>Bars</h3><table><tr><th>Preview</th><th>CSS (Size in bytes)</th><th>SMIL (Size in bytes)</th></tr><tr><td><picture><source media="(prefers-color-scheme: dark)" srcset="./preview/bars-fade-white-36.svg"><img src="./preview/bars-fade-black-36.svg"></picture></td><td><a href="./svg-css/bars-fade.svg">CSS</a> (514)</td><td><a href="./svg-smil/bars-fade.svg">SMIL</a> (625)</td></tr><tr><td><picture><source media="(prefers-color-scheme: dark)" srcset="./preview/bars-scale-white-36.svg"><img src="./preview/bars-scale-black-36.svg"></picture></td><td><a href="./svg-css/bars-scale.svg">CSS</a> (895)</td><td><a href="./svg-smil/bars-scale.svg">SMIL</a> (1891)</td></tr><tr><td><picture><source media="(prefers-color-scheme: dark)" srcset="./preview/bars-scale-fade-white-36.svg"><img src="./preview/bars-scale-fade-black-36.svg"></picture></td><td><a href="./svg-css/bars-scale-fade.svg">CSS</a> (548)</td><td><a href="./svg-smil/bars-scale-fade.svg">SMIL</a> (1244)</td></tr><tr><td><picture><source media="(prefers-color-scheme: dark)" srcset="./preview/bars-scale-middle-white-36.svg"><img src="./preview/bars-scale-middle-black-36.svg"></picture></td><td><a href="./svg-css/bars-scale-middle.svg">CSS</a> (825)</td><td><a href="./svg-smil/bars-scale-middle.svg">SMIL</a> (1891)</td></tr><tr><td><picture><source media="(prefers-color-scheme: dark)" srcset="./preview/bars-rotate-fade-white-36.svg"><img src="./preview/bars-rotate-fade-black-36.svg"></picture></td><td><a href="./svg-css/bars-rotate-fade.svg">CSS</a> (1150)</td><td><a href="./svg-smil/bars-rotate-fade.svg">SMIL</a> (894)</td></tr></table><br /><h3>Blocks</h3><table><tr><th>Preview</th><th>CSS (Size in bytes)</th><th>SMIL (Size in bytes)</th></tr><tr><td><picture><source media="(prefers-color-scheme: dark)" srcset="./preview/blocks-scale-white-36.svg"><img src="./preview/blocks-scale-black-36.svg"></picture></td><td><a href="./svg-css/blocks-scale.svg">CSS</a> (1182)</td><td><a href="./svg-smil/blocks-scale.svg">SMIL</a> (2133)</td></tr><tr><td><picture><source media="(prefers-color-scheme: dark)" srcset="./preview/blocks-shuffle-2-white-36.svg"><img src="./preview/blocks-shuffle-2-black-36.svg"></picture></td><td><a href="./svg-css/blocks-shuffle-2.svg">CSS</a> (524)</td><td><a href="./svg-smil/blocks-shuffle-2.svg">SMIL</a> (1082)</td></tr><tr><td><picture><source media="(prefers-color-scheme: dark)" srcset="./preview/blocks-shuffle-3-white-36.svg"><img src="./preview/blocks-shuffle-3-black-36.svg"></picture></td><td><a href="./svg-css/blocks-shuffle-3.svg">CSS</a> (646)</td><td><a href="./svg-smil/blocks-shuffle-3.svg">SMIL</a> (1579)</td></tr><tr><td><picture><source media="(prefers-color-scheme: dark)" srcset="./preview/blocks-wave-white-36.svg"><img src="./preview/blocks-wave-black-36.svg"></picture></td><td><a href="./svg-css/blocks-wave.svg">CSS</a> (2457)</td><td><a href="./svg-smil/blocks-wave.svg">SMIL</a> (4106)</td></tr></table><br /><h3>Pulses</h3><table><tr><th>Preview</th><th>CSS (Size in bytes)</th><th>SMIL (Size in bytes)</th></tr><tr><td><picture><source media="(prefers-color-scheme: dark)" srcset="./preview/pulse-white-36.svg"><img src="./preview/pulse-black-36.svg"></picture></td><td><a href="./svg-css/pulse.svg">CSS</a> (301)</td><td><a href="./svg-smil/pulse.svg">SMIL</a> (381)</td></tr><tr><td><picture><source media="(prefers-color-scheme: dark)" srcset="./preview/pulse-2-white-36.svg"><img src="./preview/pulse-2-black-36.svg"></picture></td><td><a href="./svg-css/pulse-2.svg">CSS</a> (400)</td><td><a href="./svg-smil/pulse-2.svg">SMIL</a> (797)</td></tr><tr><td><picture><source media="(prefers-color-scheme: dark)" srcset="./preview/pulse-3-white-36.svg"><img src="./preview/pulse-3-black-36.svg"></picture></td><td><a href="./svg-css/pulse-3.svg">CSS</a> (499)</td><td><a href="./svg-smil/pulse-3.svg">SMIL</a> (1149)</td></tr><tr><td><picture><source media="(prefers-color-scheme: dark)" srcset="./preview/pulse-multiple-white-36.svg"><img src="./preview/pulse-multiple-black-36.svg"></picture></td><td><a href="./svg-css/pulse-multiple.svg">CSS</a> (503)</td><td><a href="./svg-smil/pulse-multiple.svg">SMIL</a> (1135)</td></tr><tr><td><picture><source media="(prefers-color-scheme: dark)" srcset="./preview/pulse-ring-white-36.svg"><img src="./preview/pulse-ring-black-36.svg"></picture></td><td><a href="./svg-css/pulse-ring.svg">CSS</a> (461)</td><td><a href="./svg-smil/pulse-ring.svg">SMIL</a> (683)</td></tr><tr><td><picture><source media="(prefers-color-scheme: dark)" srcset="./preview/pulse-rings-2-white-36.svg"><img src="./preview/pulse-rings-2-black-36.svg"></picture></td><td><a href="./svg-css/pulse-rings-2.svg">CSS</a> (657)</td><td><a href="./svg-smil/pulse-rings-2.svg">SMIL</a> (1361)</td></tr><tr><td><picture><source media="(prefers-color-scheme: dark)" srcset="./preview/pulse-rings-3-white-36.svg"><img src="./preview/pulse-rings-3-black-36.svg"></picture></td><td><a href="./svg-css/pulse-rings-3.svg">CSS</a> (853)</td><td><a href="./svg-smil/pulse-rings-3.svg">SMIL</a> (1994)</td></tr><tr><td><picture><source media="(prefers-color-scheme: dark)" srcset="./preview/pulse-rings-multiple-white-36.svg"><img src="./preview/pulse-rings-multiple-black-36.svg"></picture></td><td><a href="./svg-css/pulse-rings-multiple.svg">CSS</a> (856)</td><td><a href="./svg-smil/pulse-rings-multiple.svg">SMIL</a> (1973)</td></tr></table><br /><h3>Other</h3><table><tr><th>Preview</th><th>CSS (Size in bytes)</th><th>SMIL (Size in bytes)</th></tr><tr><td><picture><source media="(prefers-color-scheme: dark)" srcset="./preview/bouncing-ball-white-36.svg"><img src="./preview/bouncing-ball-black-36.svg"></picture></td><td><a href="./svg-css/bouncing-ball.svg">CSS</a> (453)</td><td><a href="./svg-smil/bouncing-ball.svg">SMIL</a> (870)</td></tr><tr><td><picture><source media="(prefers-color-scheme: dark)" srcset="./preview/clock-white-36.svg"><img src="./preview/clock-black-36.svg"></picture></td><td><a href="./svg-css/clock.svg">CSS</a> (565)</td><td><a href="./svg-smil/clock.svg">SMIL</a> (530)</td></tr><tr><td><picture><source media="(prefers-color-scheme: dark)" srcset="./preview/eclipse-white-36.svg"><img src="./preview/eclipse-black-36.svg"></picture></td><td><a href="./svg-css/eclipse.svg">CSS</a> (377)</td><td><a href="./svg-smil/eclipse.svg">SMIL</a> (333)</td></tr><tr><td><picture><source media="(prefers-color-scheme: dark)" srcset="./preview/eclipse-half-white-36.svg"><img src="./preview/eclipse-half-black-36.svg"></picture></td><td><a href="./svg-css/eclipse-half.svg">CSS</a> (385)</td><td><a href="./svg-smil/eclipse-half.svg">SMIL</a> (341)</td></tr><tr><td><picture><source media="(prefers-color-scheme: dark)" srcset="./preview/gooey-balls-1-white-36.svg"><img src="./preview/gooey-balls-1-black-36.svg"></picture></td><td><a href="./svg-css/gooey-balls-1.svg">CSS</a> (774)</td><td><a href="./svg-smil/gooey-balls-1.svg">SMIL</a> (1028)</td></tr><tr><td><picture><source media="(prefers-color-scheme: dark)" srcset="./preview/gooey-balls-2-white-36.svg"><img src="./preview/gooey-balls-2-black-36.svg"></picture></td><td><a href="./svg-css/gooey-balls-2.svg">CSS</a> (1064)</td><td><a href="./svg-smil/gooey-balls-2.svg">SMIL</a> (853)</td></tr><tr><td><picture><source media="(prefers-color-scheme: dark)" srcset="./preview/tadpole-white-36.svg"><img src="./preview/tadpole-black-36.svg"></picture></td><td><a href="./svg-css/tadpole.svg">CSS</a> (398)</td><td><a href="./svg-smil/tadpole.svg">SMIL</a> (354)</td></tr><tr><td><picture><source media="(prefers-color-scheme: dark)" srcset="./preview/wifi-white-36.svg"><img src="./preview/wifi-black-36.svg"></picture></td><td><a href="./svg-css/wifi.svg">CSS</a> (999)</td><td><a href="./svg-smil/wifi.svg">SMIL</a> (1238)</td></tr><tr><td><picture><source media="(prefers-color-scheme: dark)" srcset="./preview/wifi-fade-white-36.svg"><img src="./preview/wifi-fade-black-36.svg"></picture></td><td><a href="./svg-css/wifi-fade.svg">CSS</a> (989)</td><td><a href="./svg-smil/wifi-fade.svg">SMIL</a> (1172)</td></tr><tr><td><picture><source media="(prefers-color-scheme: dark)" srcset="./preview/wind-toy-white-36.svg"><img src="./preview/wind-toy-black-36.svg"></picture></td><td><a href="./svg-css/wind-toy.svg">CSS</a> (1321)</td><td><a href="./svg-smil/wind-toy.svg">SMIL</a> (1276)</td></tr></table><br />

## Adaptation

[React Component Library by dephraiim](./LICENSE)

## License

MIT © [Utkarsh Verma](https://github.com/n3r4zzurr0)
