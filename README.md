# Medienreaktor.CookieConsent
Cookie Consent for Neos, based on https://cookieconsent.insites.com

## Installation
This package is not yet on Packagist, but will be soon. In the meantime, it can be used by adding the repository URL to your composer.json and require medienreaktor/cookieconsent@dev-master.

## Configuration
Configuration options can be seen in Settings.yaml. In the settings-array, most settings of the original Cookie Consent JavaScript can be configured, e.g.

```
Medienreaktor:
  CookieConsent:
    settings:
      type: 'opt-out'
      position: 'top'
      theme: 'block'
      palette:
        popup:
          background: '#237afc'
          text: '#fff'
        button:
          background: '#fff'
          text: '#237afc'
```

If you want to set your own "Learn more"-link, you have to set a Node identifier:

```
Medienreaktor:
  CookieConsent:
    informationNode: '#5a30fe73-e487-4301-a547-838b6440e33d'
```

## License
Licensed under MIT license, as is the original Cookie Consent JavaScript by Insites.
