# pyTranscriber

pyTranscriber is an application that can be used to generate <b>automatic transcription / automatic subtitles </b> for audio/video files through a friendly graphical user interface. The hard work of speech recognition is made by the <a href="https://cloud.google.com/speech/">Google Speech Recognition API</a> using <a href="https://github.com/agermanidis/autosub">Autosub</a>.
<br>
<br>
![pyTranscriber1](doc/screenshot3.png?raw=true "pyTranscriber")
<br>
<br>
pyTranscriber is a improved version of my previous project <a href="https://github.com/raryelcostasouza/JAutosub">JAutosub (Java)</a>, created because of the limitations, issues, and overhead of mixing this 2 different languages on a single project.
<br>
<br>
The app by default outputs the subtitles as .srt and the transcribed audio on the user interface as well  as .txt files. SRT Files can be edited using <a href="http://www.aegisub.org/">Aegisub</a>.
Internet connection is REQUIRED because it uses the <a href="https://cloud.google.com/speech/">Google Cloud Speech Server</a> for the job, in the same way as the <a href="https://support.google.com/youtube/answer/6373554?hl=en">Youtube Automatic Subtitles</a>.
<br>
<br>
IMPORTANT: As speech recognition technology is still not fully accurate, the <b>accuracy</b> of the result can vary a lot, depending on many factors, mainly the <b>quality/clarity</b> of the audio. Ideally the audio input should not have background noise, sound effects or music. If there is a single speaker and he speaks in a clear and slow speed seems that the recognition is much more accurate. Sometimes, under ideal/lucky conditions it is possible to get a <a href="https://medium.com/@mlockrey/youtube-s-incredible-95-accuracy-rate-on-auto-generated-captions-b059924765d5">accuracy result close to 95%</a>.
<br>
<br>
![pyTranscriber2](doc/screenshot2.png?raw=true "pyTranscriber")
![pyTranscriber3](doc/screenshot1.png?raw=true "pyTranscriber")
<br>
<br>
<h1>For Users - Download the Windows/Linux/MacOS portable app</h1>
<a href="https://github.com/raryelcostasouza/pyTranscriber/releases/tag/v1.2-stable"> pyTranscriber-v1.2-stable</a>

<h1>For Developers - Technical Details</h1>
Check at <a href="https://github.com/raryelcostasouza/pyTranscriber/blob/master/doc/technical_details.md">technical_details.md<a>

### License

GPL v3
