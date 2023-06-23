# flutter_google_places_autocomplete

<p align="center">
<a href="https://github.com/dev-juju/flutter_google_places_autocomplete/actions?query=workflow%3ADart"><img src="https://github.com/dev-juju/flutter_google_places_autocomplete/workflows/Dart/badge.svg?branch=master" alt="Build Status"></a>
<a href="https://codecov.io/gh/dev-juju/flutter_google_places_autocomplete"><img src="https://codecov.io/gh/dev-juju/flutter_google_places_autocomplete/branch/master/graph/badge.svg" alt="codecov"></a>
<a href="https://github.com/dev-juju/flutter_google_places_autocomplete"><img src="https://img.shields.io/github/stars/dev-juju/flutter_google_places_autocomplete.svg?style=flat&logo=github&colorB=deeppink&label=stars" alt="Star on Github"></a>
<a href="https://bmc.link/bomdi" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/default-orange.png" alt="Buy Me A Coffee" height="25px"></a>
</p>

Google places autocomplete widgets for flutter.

**NB:** You need to enable billing on your google account to utilize place autocomplete services.


## Installation

In the `dependencies:` section of your `pubspec.yaml`, add the following line:

```yaml
dependencies:
  flutter_google_places_autocomplete: <latest_version>
```

## Usage

```dart
const kGoogleApiKey = "API_KEY";

Prediction p = await PlacesAutocomplete.show(
  context: context,
  apiKey: kGoogleApiKey,
  mode: Mode.overlay, // Mode.fullscreen
  language: "fr",
  components: [new Component(Component.country, "fr")]
);
```

### Examples:
<div style="text-align: center">
  <table>
    <tr>
      <td style="text-align: center">
        <img src="https://raw.githubusercontent.com/fluttercommunity/flutter_google_places/master/flutter_01.png" height="400">
      </td>
      <td style="text-align: center">
        <img src="https://raw.githubusercontent.com/fluttercommunity/flutter_google_places/master/flutter_02.png" height="400">
      </td>
    </tr>
  </table>
</div>

## Feature Requests and Issues

Please file feature requests and bugs at the [issue tracker][tracker].

[tracker]: https://github.com/dev-juju/flutter_google_places_autocomplete/issues/new
