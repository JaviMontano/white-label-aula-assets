Gallery previews are original MIT vector compositions. Extract this archive alongside the matching runtime bank: it creates gallery/ and never replaces the runtime manifest. MetodologIA gallery reads the OFL fonts already present in ../fonts; font files and copyright notices remain in the runtime bank. No network is required. Preview variants do not count as additional scenes.

Native search matches meaning, tags, uses, title and ID. It ignores accents and letter case, combines query words, announces the result count and restores focus after clearing. No network or JavaScript dependency is required.

Reproducibility in the Frames source checkout: build-aula-gallery.py is the two-stage entrypoint (frozen build-aula-assets.py, then search overlay). Use --dest RELEASE --canonical --check to verify both the complete release and canonical geometry. The older builder alone describes the baseline gallery.
