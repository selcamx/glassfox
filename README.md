<p align="center">
  <a href="https://glassfox.ai">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset=".github/glassfox-lockup-light.svg">
      <img src=".github/glassfox-lockup-dark.svg" width="300" alt="Glassfox">
    </picture>
  </a>
</p>

<p align="center">
  A Mac app for dictation, meeting notes, and finding your way back to your work.<br>
  Powered by local models. Your work stays on your Mac by default.
</p>

<p align="center">
  <a href="https://github.com/selcamx/glassfox/releases/latest"><b>Download for macOS</b></a>
  &nbsp; · &nbsp; <a href="https://glassfox.ai">Website</a>
  &nbsp; · &nbsp; <a href="https://github.com/selcamx/glassfox/releases">Release notes</a>
  &nbsp; · &nbsp; <a href="https://github.com/selcamx/glassfox/issues">Report an issue</a>
</p>

<p align="center">
  <sub>Apple Silicon · macOS 15 or later · English dictation and meetings</sub>
</p>

> **Glassfox 1.6 preview.** This page describes the upcoming Glassfox release. The latest public download is currently Chirp 1.5.4. Existing Chirp licenses and saved recordings carry over to Glassfox.

Glassfox started as Chirp, a way to dictate and transcribe meetings on a Mac.
It now connects those recordings with an optional timeline of your work, so you
can return to what you were doing and ask questions with the relevant context.

## From a recording to the work around it

### Speak

Dictate into the app you're using, or record a meeting with your microphone and
the call's audio. Meeting Mode labels speakers without sending a bot into the
call. Saved recordings have searchable transcripts, playback, and tags.

Solo dictation is free. Live Solo text is also free with the optional live
component installed and enabled. Meeting Mode is included in Pro.

### Recall

Find the page you were reading or the document you had open around a meeting.
When you turn it on, Recall builds a timeline from the apps you use and the
readable context macOS makes available. It connects that activity to your saved
recordings.

Recall is opt-in. Captured text and descriptive context are encrypted on your
Mac and kept for 30 days by default. You can pause collection, exclude apps,
change retention, inspect, export, or delete it. Recall does not keep a screenshot
archive.

### Ask

Ask about a recording or the Recall context from a day or date range. Add a file
or your current screen when it helps, then open the sources behind the answer.
Pro can also turn recordings into summaries, cleaned notes, or email drafts,
and create daily briefs from Recall.

Ask runs locally by default after its models are downloaded. Optional cloud
answers use your own API key, with provider charges billed separately.

## Start free

| | Starter | Pro |
| --- | --- | --- |
| Price | Free, without a time limit | $39 once |
| Solo dictation and saved recordings | Included | Included |
| Transcript search, playback, and tags | Included | Included |
| Recall collection and privacy controls | Included, opt-in | Included, opt-in |
| Recall browsing | Today's full timeline and earlier-day overviews | Full retained timeline and historical search |
| Meeting Mode with speaker labels | | Included |
| New Ask answers, summaries, and daily briefs | | Included |

The **10-day Pro trial** starts when you choose a Pro feature, not during setup
or model downloads. No card or account is required to try it. Saved recordings,
answers, briefs, and documents stay readable after the trial ends.

Pro covers one active Mac at a time, can move with you to another Mac, and includes
future updates. Existing Chirp licenses keep their original activation limits.
Pro can use only Recall context that was captured and is still retained; it
cannot recover deleted, expired, or uncaptured activity.

## What stays on your Mac

Transcription, speaker recognition, and Recall collection run locally. Local Ask
also processes your questions and context on the Mac.

If you choose cloud answers, your question, recent conversation, and selected
text context go directly to the provider. That text may include excerpts from
recordings, Recall, files, and your screen. The cloud answer request does not
upload raw audio, files, screenshots, or images.

Optional web research sends a public search query to a search provider and
retrieves selected pages. Downloads, updates, license checks, and optional
analytics also use the internet. If you connect an external assistant through
MCP, that client's settings determine how it handles the transcript excerpts
it reads.

[Read the privacy policy](https://glassfox.ai/privacy).

## Get started

1. Download the latest installer from [GitHub Releases](https://github.com/selcamx/glassfox/releases/latest) and move the app to Applications.
2. Follow setup to grant permissions and download the dictation model. Meeting and Ask models download when you choose those features.
3. Try a dictation with your chosen shortcut. Turn on Recall if you'd like to keep a timeline of your work.

Glassfox requires an Apple Silicon Mac, M1 or newer, running macOS 15 or later.
Dictation and meeting transcription currently support English.

## Support

This is the public release and issue-tracking repository for Glassfox, a commercial
macOS app. The app's source code is not published here.

[Report a bug or request a feature](https://github.com/selcamx/glassfox/issues).
For private support or billing questions, email [hello@glassfox.ai](mailto:hello@glassfox.ai).
