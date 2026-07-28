## [2.2.1](https://github.com/5-stones/keycloak-email-otp/compare/2.2.0...2.2.1) (2026-07-28)


### Features

* expose masked email, code length and TTL to the login form and email ([8d7247f](https://github.com/5-stones/keycloak-email-otp/commit/8d7247f489c17229c6dc4059bb4b9c0065e0983e))



# [2.2.0](https://github.com/5-stones/keycloak-email-otp/compare/2.0.0...2.2.0) (2026-01-22)


### Bug Fixes

* fix retry counting when set to Required and display of remaining attempts ([6361f64](https://github.com/5-stones/keycloak-email-otp/commit/6361f641f0fdb8dbfa157894682612d82d03a0a3))
* **messages_en:** add proper single quote escaping ([656a1ce](https://github.com/5-stones/keycloak-email-otp/commit/656a1ce726526fbdc3250d6ce9a4f0c2e2c3b5b9))
* **translations:** remove erroneous s in emailTOTPBody ([ed434db](https://github.com/5-stones/keycloak-email-otp/commit/ed434db5bba33c898f90237a7bd4506dab7d6aa7))


### Features

* automatically set email as verified when successful ([19129a2](https://github.com/5-stones/keycloak-email-otp/commit/19129a298c197d0a4079a5f695d6ef703b619b1c))
* enhance OTP email functionality by adding "resend email" capability ([#22](https://github.com/5-stones/keycloak-email-otp/issues/22)) ([84b8674](https://github.com/5-stones/keycloak-email-otp/commit/84b86744c9cf42d2f9ce47132cab09ca99f5b2e2))



# [2.0.0](https://github.com/5-stones/keycloak-email-otp/compare/90f59898e08b7eed5fa4cc838b244907aa2a329c...2.0.0) (2023-11-02)


### Bug Fixes

* **build:** update keycloak version dependency to fix NoSuchMethodError on 21.0.2 ([6f6fc3b](https://github.com/5-stones/keycloak-email-otp/commit/6f6fc3b3a2f231ea6cb2b5823c1bc69785ee0be2))


### Features

* ***/*:** add basic functionality for emailed TOTP login ([90f5989](https://github.com/5-stones/keycloak-email-otp/commit/90f59898e08b7eed5fa4cc838b244907aa2a329c))
* **build:** change the name of artifact ([1d3ac00](https://github.com/5-stones/keycloak-email-otp/commit/1d3ac00c2c4fb9d6fb1b87910a28aee10c37dc15))
* **config:** add the ability to configure the email subject ([6294b28](https://github.com/5-stones/keycloak-email-otp/commit/6294b283e40898d0817ff1d81015fef384837e71))
* **config:** add the ability to specify a max number of retries before forcing a restart ([ba3a147](https://github.com/5-stones/keycloak-email-otp/commit/ba3a1472e1f0a26882cea26258d2f8167c7eaa51))
* **config:** allow the ability to configure code character sets:  uppercase, lowercase, and numbers ([288ff6c](https://github.com/5-stones/keycloak-email-otp/commit/288ff6c5d7c78900211be8d2373d5c9f0a5b1724))
* **config:** remove unused "senderId" config ([7d96fe3](https://github.com/5-stones/keycloak-email-otp/commit/7d96fe32aa31446e664a6d1d5754c97650adcd73))
* **config:** respect the setting of the simulation configuration option ([93ffe23](https://github.com/5-stones/keycloak-email-otp/commit/93ffe239297a52e8771c1363777d602bcd761534))
* **email, translations:** add proper HTML email sending and update outdated translations ([b83c011](https://github.com/5-stones/keycloak-email-otp/commit/b83c0115faa1448b17c356864be2eda9311d6e59))
* **emailotpauthenticator.java:** display remaining attempts ([024ac12](https://github.com/5-stones/keycloak-email-otp/commit/024ac12aace9a4bfab531acb6b2d85a2a6004232))
* **emailotpauthenticator.java:** update email totp code invalid ([22f5eb3](https://github.com/5-stones/keycloak-email-otp/commit/22f5eb35f289975528039c662f9ff717e0bd45f0))
* **messages:** add translations for select authentication page ([5ede3ce](https://github.com/5-stones/keycloak-email-otp/commit/5ede3ce6bb198023037859dcea734c7b9bd6563e))
* update for Keycloak 22 ([da56e1b](https://github.com/5-stones/keycloak-email-otp/commit/da56e1bfe0239321aece0750c36cf70c1307d6ed))


### BREAKING CHANGES

* Will no longer run on Java<17 and may not run if Keycloak 21 doesn't include
jakarta.



