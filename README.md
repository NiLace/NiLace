# NL Sounds

**Analogue audio, modelled from the schematic. LV2 plugins for Linux.**

I'm Luis, a guitarist, bassist and home mixing engineer based in Madrid. NL Sounds is where I build the tools I
want to hear on my own records: consoles and pedals rebuilt from their circuits, component by component, rather
than fitted to a curve or captured from a unit. Everything is tested where it will be used — in real sessions,
in [Ardour](https://ardour.org), on Linux.

---

## Pedals

<table>
<tr>
<td width="33%" align="center" valign="top">
<a href="https://github.com/NiLace/TheOmegaCake">
<img src="https://raw.githubusercontent.com/NiLace/TheOmegaCake/main/assets/images/panel.png" alt="The Omega Cake" height="220">
</a>
<h3><a href="https://github.com/NiLace/TheOmegaCake">The Omega Cake</a></h3>
<b>Fuzz · 45 circuits</b><br><br>
The four-transistor fuzz of 1969 and the whole family that grew out of it: original boards, op-amp versions, clones and mods, each solved from its components.
</td>
<td width="33%" align="center" valign="top">
<a href="https://github.com/NiLace/ValveHowler">
<img src="https://raw.githubusercontent.com/NiLace/ValveHowler/main/assets/images/panel.png" alt="Valve Howler" height="220">
</a>
<h3><a href="https://github.com/NiLace/ValveHowler">Valve Howler</a></h3>
<b>Smooth overdrive</b><br><br>
The classic screamer-style overdrive for guitar and bass, with selectable circuit variants and coefficients generated straight from the netlist.
</td>
<td width="33%" align="center" valign="top">
<a href="https://github.com/NiLace/BlueBrigade">
<img src="https://raw.githubusercontent.com/NiLace/BlueBrigade/main/assets/images/panel.png" alt="Blue Brigade" height="220">
</a>
<h3><a href="https://github.com/NiLace/BlueBrigade">Blue Brigade</a></h3>
<b>Analogue chorus · 1979</b><br><br>
The little blue box that became the sound of the 1980s: a bucket-brigade delay line and a triangle LFO, modelled stage by stage.
</td>
</tr>
</table>

## Amps, studio & tools

<table>
<tr>
<td width="33%" align="center" valign="top">
<a href="https://github.com/NiLace/MK81">
<img src="https://raw.githubusercontent.com/NiLace/MK81/main/assets/images/panel.png" alt="MK 81" width="240">
</a>
<h3><a href="https://github.com/NiLace/MK81">MK 81</a></h3>
<b>British valve amp head</b><br><br>
The early-1980s master-volume lead head, in four power-valve versions and two power-supply eras, with a power stage that sags and growls when pushed.
</td>
<td width="33%" align="center" valign="top">
<a href="https://github.com/NiLace/Dynamo0C">
<img src="https://raw.githubusercontent.com/NiLace/Dynamo0C/main/assets/images/panel.png" alt="Dynamo 0C" height="220">
</a>
<h3><a href="https://github.com/NiLace/Dynamo0C">Dynamo 0C</a></h3>
<b>Console-style 4-band EQ · stereo</b><br><br>
Four proportional-Q bands, high- and low-pass filters and a channel drive, with curves that keep their analogue shape up to Nyquist.
</td>
<td width="33%" align="center" valign="top">
<a href="https://github.com/NiLace/TheMonoHawk">
<img src="https://raw.githubusercontent.com/NiLace/TheMonoHawk/main/assets/images/mono_front_panel.png" alt="The Mono Hawk" width="240">
</a>
<h3><a href="https://github.com/NiLace/TheMonoHawk">The Mono Hawk</a></h3>
<b>Chromatic tuner</b><br><br>
Sub-cent tracking down to a 5/6-string bass low B, a strobe view, 50 tunings and a reference tone, in a rack-unit display.
</td>
</tr>
</table>

---

## How I work

- **From the circuit, not from a capture.** Component values, pot laws and topology come from published schematics
  and traces; each model documents where its values come from.
- **Honest about the limits.** Every README has a *What it doesn't model* section.
- **Built with AI, validated by ear.** I design the plugins, their sound and their interfaces, and direct
  [Claude](https://claude.ai) to write the code. Then I check the results against simulation and use them in real
  mixes before anything is released.
- **Free software.** All plugins are released under the AGPL-3.0.

---

## Get them

Each repo has prebuilt bundles under **Releases**. Extract the `.lv2` folder into `~/.lv2/` and rescan in your
host. Building from source is a `make` / `cmake` away; see each README.

## Contact

nilace@nylarea.com · bug reports and ideas welcome in each repo's Issues
