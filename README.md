# Typio

Typio is an English IEM for non-native speakers on macOS. It is built for people who write in English every day but still lose flow on spelling, word choice, or switching between input methods.

Typio is especially useful for Korean, Japanese, and Chinese users who want a clean English-first typing experience instead of full Chinese IME behavior.

Everything is local-first: no cloud dependency, no sign-in flow, and no extra distractions. You type, Typio suggests practical candidates, and you keep writing.

Typio means the end of typo.

## Screenshots

<table>
	<tr>
		<td align="center"><strong>Input Source Menu</strong></td>
		<td align="center"><strong>Language Mode Switch</strong></td>
	</tr>
	<tr>
		<td align="center"><img src="resources/images/readme/typio-menu-entry.png" alt="Typio input source menu" height="240" /></td>
		<td align="center"><img src="resources/images/readme/typio-language-toggle.png" alt="Typio language toggle" height="240" /></td>
	</tr>
	<tr>
		<td align="center"><strong>Multi-row Candidate Panel</strong></td>
		<td align="center"><strong>Settings: Panel Style</strong></td>
	</tr>
	<tr>
		<td align="center"><img src="resources/images/readme/typio-candidate-grid.png" alt="Typio candidate grid" height="240" /></td>
		<td align="center"><img src="resources/images/readme/typio-settings-panel-style.png" alt="Typio settings panel style" height="240" /></td>
	</tr>
</table>

## Install

For end users, download and run `typio-<version>.pkg`, then enable Typio in System Settings → Keyboard → Input Sources.

In most cases, logout is not required. If Typio does not appear immediately, remove and add the source once. If it still does not show, log out and log back in.

## Build and Package

Use `sh scripts/build.sh` to build the app, `sh scripts/build-and-install.sh` for local developer install, and `sh scripts/package-pkg.sh` to generate the installer package at `dist/typio-<version>.pkg`.

If you need installer signing, set `INSTALLER_SIGN_IDENTITY` before packaging.

## About

Project home: https://github.com/howtousellm/typio
