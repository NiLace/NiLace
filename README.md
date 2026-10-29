# NL Sounds

**Analogue audio, modelled from the schematic. LV2 plugins for Linux.**

I'm Luis, a guitarist, bassist and home mixing engineer based in Madrid. NL Sounds is where I build the tools I
want to hear on my own records: consoles and pedals rebuilt from their circuits, component by component, rather
than fitted to a curve or captured from a unit. Everything is tested where it will be used — in real sessions,
in [Ardour](https://ardour.org), on Linux.

---

## Plugins

<table>
<tr>
<td width="50%" align="center" valign="top">
<a href="https://github.com/NiLace/Dynamo0C">
<img src="https://raw.githubusercontent.com/NiLace/Dynamo0C/main/assets/images/panel.png" alt="Dynamo 0C EQ" width="180">
</a>
<h3><a href="https://github.com/NiLace/Dynamo0C">Dynamo 0C</a></h3>
<b>Console-style 4-band EQ</b> · stereo<br><br>
Four proportional-Q bands, high- and low-pass filters and an asymmetric channel drive, voiced like the channel
strip of a classic analogue desk. Each band comes from the circuit's transfer function, so the curves keep their
analogue shape all the way up to Nyquist.
</td>
<td width="50%" align="center" valign="top">
<a href="https://github.com/NiLace/TheOmegaCake">
<img src="https://raw.githubusercontent.com/NiLace/TheOmegaCake/main/assets/images/panel.png" alt="The Omega Cake" width="180">
</a>
<h3><a href="https://github.com/NiLace/TheOmegaCake">The Omega Cake</a></h3>
<b>Four-transistor fuzz, 45 circuits</b> · mono<br><br>
The 1969 fuzz and the whole family that grew out of it: original boards, op-amp versions, clones and mods. Every
model is solved from its components and checked against a circuit simulator.
</td>
</tr>
</table>

<!--
## In the workshop

Add upcoming plugins here once they have a public repo, e.g.:
- **The Shrike** — brickwall limiter
-->

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
