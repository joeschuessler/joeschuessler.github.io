# 9-29-2025 - Aerys' physical topology of services and hosting
## What I worked on
- Started thinking about future state for when I start splitting Aerys' cores up into separate locations. I considered making that change now and splitting the repo or even restructuring it AGAIN... it's gone through so many of those, it's fragmented as fuck and I'm STILL working to catch all the discussions and ideas I've had up to present-state and stable. Had GPT help me write a `services/` subdirectory and an example set of files for deployment for the future, so that I could document all my subcore modularity and also containerize them for easy deployment and upgrade.

## Problems or stuck points
- Nothing in particular more than the fact that I wanted to keep this idea or thought on hand; I've been developing in a single machine, starting services in the same place as where the code is under edit. I never factored in the inevitability of multiple machines, even though I've had that vision in my head the whole time.

## Small wins
- I can at least say that I have the entirety of the most basic skeletal version of this idea documented and in place for future reflection or ingestion by Copilot.

## Next nudge
- I really need to make more progress in defragmenting the execution path. I have a whole 3080-loaded host ready for Aerys' heavy lifting, but she's not even stable.

## Random thoughts
- Maybe just a rudimentary React client to talk back and forth with Aerys? Seems like a lot of work just to completely eschew it once ASR/TTS are running.
- I need to think about how much of the ASR/TTS *needs* to be embedded in real-time, versus things that can be queued for quiet hours.