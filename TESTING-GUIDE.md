# PhantomEye Beta Testing Guide

## Before installing

- Read [PRIVACY.md](PRIVACY.md).
- Install only an APK linked from this repository's official GitHub Releases page.
- Check that the release notes identify the version being tested.
- Do not install a build if you cannot verify where it came from.
- Back up anything important. Beta software may contain defects.

**There is currently no beta APK published.** This guide is preparatory. Do not begin a test until an official release and its instructions are available.

## Test objective

Record whether PhantomEye continues to function during ordinary background use. A test should help distinguish among:

- The app or service stopped.
- The app crashed.
- A scheduled task did not run.
- A feature stopped working while the app remained open.
- The phone was restarted or the app was manually force-stopped.

A phone showing no notification or no recent event does not, by itself, prove that Android killed the process.

## Suggested test procedure

When a release-specific test plan is published:

1. Record the phone manufacturer and model, Android version, and PhantomEye version.
2. Record the battery optimization and background-app settings relevant to PhantomEye.
3. Set up PhantomEye using the release instructions.
4. Note the exact start time.
5. Use the phone normally. Do not force-stop PhantomEye or clear its data during the test.
6. If PhantomEye stops responding, note the time and what you observed.
7. If you manually reopen the app, record that time too.
8. Submit the report below. Do not include private content or sensitive identifiers.

Keep the phone's normal battery settings unless the test plan specifically asks you to change one. If you change a setting, record what changed and when.

## Test report template

Copy and complete:

- Device manufacturer/model:
- Android version:
- PhantomEye version:
- Test start date and time (include timezone):
- Test end date and time:
- Battery optimization setting for PhantomEye:
- Other relevant background restrictions:
- Did the phone restart during the test?:
- Did PhantomEye stop responding?:
- Approximate time first noticed:
- What exactly stopped working?:
- Did reopening PhantomEye restore it?:
- Any steps taken before the problem:
- Additional notes:

You may attach a screenshot of relevant app settings or an error message, after checking that it contains no personal information.

## What not to send

Never send passwords, OTPs, private messages, personal photographs, precise home addresses, or unrelated device data. Do not send camera captures or location history as a test report.

## Important limitation

Android generally cannot guarantee that an app will execute code after its own process has been abruptly terminated. A missing in-app log entry is therefore not definitive proof of a process kill. The developer may request additional, clearly explained diagnostic steps for a particular release.
