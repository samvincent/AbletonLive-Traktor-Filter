# Traktor style Cut-Off Filter
## for Ableton Live

Traktor's Low/Hi pass filter is simple and useful. There is no preset for such a thing in **Live**, but we can make one using ableton's **Audio Effects Rack** device.

![S4 filter](https://github.com/samvincent/AbletonLive-Traktor-Filter/raw/master/support/S4-filter.png) **≈** ![Traktor Filter view](https://github.com/samvincent/AbletonLive-Traktor-Filter/raw/master/support/TraktorFilter-view.png)

## MIDI Setup
Just set any knob on a midi controller connected to *Live*.

You need to set the range from `1` through `127` or the effect will be passed through when the knob is all the way left.

![MIDI Setup](https://github.com/samvincent/AbletonLive-Traktor-Filter/raw/master/support/midi-setup.png)

You may want to MIDI map the `device on/off` switch to a button located close to the knob (on your **APC 40** for example) so you don't have to worry about whether the effect is centered at `64` or not.

## Install

[Download](https://github.com/samvincent/AbletonLive-Traktor-Filter/raw/master/Traktor%20Filter.adg) and double-click the file `Traktor Filter.adg` to open in *Live*.

You can also clone and copy to your computer's **Performance & DJ** presets folder with the following commands:

	git clone https://github.com/samvincent/AbletonLive-Traktor-Filter.git
	cp AbletonLive-Traktor-Filter/Traktor\ Filter.adg ~/Library/Application\ Support/Ableton/Library/Presets/Audio\ Effects/Audio\ Effect\ Rack/Performance\ \&\ DJ/Traktor\ Filter.adg

##### Credit

I first made this by following a tutorial posted on a forum about the technique used.

I can't seem to find the original post, sorry :worried:
