// Old webkitAudioContext code:
var osc = context.createOscillator();
osc.type = osc.SINE;     // sine waveform
osc.type = osc.SQUARE;   // square waveform
osc.type = osc.SAWTOOTH; // sawtooth waveform
osc.type = osc.TRIANGLE; // triangle waveform
osc.setWaveTable(table);
var isCustom = (osc.type == osc.CUSTOM); // isCustom will be true

https://developer.mozilla.org/en-US/docs/Web/API/Web_Audio_API/Migrating_from_webkitAudioContext