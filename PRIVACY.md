# NightPlay 0.0.4 privacy information

NightPlay stores settings, cache data, thumbnails, and diagnostic information
locally under the current Windows user profile. Clips, recordings, screenshots,
and GIFs are saved only to folders selected in NightPlay.

NightPlay does not send analytics or telemetry by default. It contacts GitHub to
check for NightPlay updates when update checking is enabled. Actions that upload or
share media contact the service explicitly chosen by the user.

Diagnostic bundles are created locally and redact configured personal paths. They
are not uploaded automatically. Users should still review a bundle before sharing
it because logs can describe hardware, Windows versions, and capture settings.
