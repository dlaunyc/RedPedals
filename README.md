# RedPedals
A programmable digital guitar effects pedal and a mobile companion app for creating, saving, sharing, and performing with custom tones.
Project overview

The goal is to give guitarists a flexible digital pedalboard that is easy to configure and practical to use while playing. A mobile app will provide detailed tone editing, while the physical pedal will process the guitar signal and recall saved presets independently.

The system has two intended modes:

- **Practice Mode:** Create a signal chain, adjust effect parameters, and hear changes as they are made.
- **Performance Mode:** Use presets stored on the pedal and switch between them through physical controls, without requiring a phone or internet connection.

The project combines analog electronics, embedded programming, digital signal processing (DSP), mobile interface design, and communication between hardware and software.

## Inspiration and design goals

The central idea is to bring the flexibility of an editable digital pedalboard into a dedicated piece of guitar hardware. A tone should be something a guitarist can experiment with, save, revisit during a performance, and share with another player.

The design draws on the familiar workflow of arranging individual pedals into a signal chain. The app extends that workflow with editable effect order, reusable presets, numerical controls, and performance arrangements. The physical pedal provides access to prepared sounds while the guitarist is playing.

Ease of use, practicality, and accessibility guide the project. Detailed editing belongs in an interface with enough space to show the controls clearly; performing requires dependable access to saved sounds. Core local functionality should work without an account, and playing should remain possible without internet access.

The main goals are to:

1. **Process guitar audio locally.** Run effects on the pedal and develop a usable audio path from guitar input to amplifier output.
2. **Make tone creation approachable.** Let users add effects from a library, change their order, and adjust controls while listening.
3. **Make sounds reusable.** Save individual effect setups and complete signal chains, then recall them from the pedal.
4. **Support preparation for live playing.** Organize presets into ordered performance arrangements with groups and notes.
5. **Enable sharing.** Include preset sharing by link in the planned first app version, with broader community features considered later.
