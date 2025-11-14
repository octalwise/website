---
title: Acidity
---

{% header() %}
{{ title(title="Acidity") }}

{{ icon(name="download") }} [Download on the App Store](https://apps.apple.com/us/app/acidity-view-page-archives/id6472630023)
{% end %}

{% section() %}
Acidity is a Safari extension for navigating to archived versions of pages.

![Screenshot of archived version of New York Times article.](acidity/assets/archive.png)
{% end %}

{% section() %}
## Questions

{% details(summary="How do I change the extension settings?") %}
You can change the extension settings by opening preferences, switching to the extensions panel, selecting Acidity, and clicking the settings button.

![Screenshot of the extension in Safari settings.](acidity/assets/settings.png)
{% end %}

{% details(summary="What are matches and how do I use them?") %}
Matches are used for automatically navigating to archived versions of pages depending on the URLs.
They can be added in the extension settings. For more information, see 'How do I change the extension settings?'.
{% end %}

{% details(summary="What is the syntax used for matches?") %}
Matches are JavaScript regexes created using the <code>RegExp</code> class.
They are modified to match the entire URL, so surrounding the regex with <code>^</code> and <code>$</code> is not necessary.
For more information about regexes, see the [MDN documentation](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Regular_Expressions) on them.
{% end %}
{% end %}

{% section() %}
## Privacy

Acidity does not collect any data.

{% details(summary="Why are certain permissions required?") %}
* `activeTab`: Used for navigating to the archived version of the current tab.
* `tabs`: Used for navigating to archived versions of matched tabs.
* `storage`: Used for storing and persisting settings across browser restarts.
{% end %}
{% end %}

{% section() %}
## Contact

Send emails to [acidity@octalwise.com](mailto:tracks@octalwise.com).
{% end %}
