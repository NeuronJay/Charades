<p align="center">
  <img src="screenshots/logo.png?raw=true" alt="Party Flutter" />
</p>

Mobile party game implemented in Flutter framework. Its been heavily inspired by the Heads Up! game:

- Get a group of friends (at least 3 players)
- Start the app
- The youngest player takes the phone
- Pick one of the available categories/topics (eg. Animals, TV series, Sport)
- Place the phone at your forehead, so that other players can see the screen
- Guess the word displayed at the screen - your friends are here to help you!

## Generate translations

- `flutter pub pub run intl_translation:extract_to_arb --output-dir=lib/l10n lib/localizations.dart`
- `flutter pub pub run intl_translation:generate_from_arb --output-dir=lib/l10n --no-use-deferred-loading lib/localizations.dart lib/l10n/intl_*.arb`

## Resources

- [Icons](https://www.baianat.com/resources/thousands/)
