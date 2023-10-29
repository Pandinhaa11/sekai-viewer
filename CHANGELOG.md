# Changelog

All notable changes to this project will be documented in this file. See [standard-version](https://github.com/conventional-changelog/standard-version) for commit guidelines.

## [1.8.0](https://github.com/Sekai-World/sekai-viewer/compare/v1.7.6...v1.8.0) (2023-10-29)


### Bug Fixes

* :bug: music list crash if sorting by play levels ([a818545](https://github.com/Sekai-World/sekai-viewer/commits/a81854546d2f62081927534e2c350ff95adb5031)), closes [#451](https://github.com/Sekai-World/sekai-viewer/issues/451)
* :lipstick: weird font fallback ([a0c6106](https://github.com/Sekai-World/sekai-viewer/commits/a0c6106d82b55ff5aa946adc3a8a4170d142f8cb)), closes [#427](https://github.com/Sekai-World/sekai-viewer/issues/427)

### [1.7.6](https://github.com/Sekai-World/sekai-viewer/compare/v1.7.5...v1.7.6) (2023-10-28)


### Bug Fixes

* :bug: card list not loading for tw and kr server ([adf8f2c](https://github.com/Sekai-World/sekai-viewer/commits/adf8f2cbbc9091c06d7ea3d8635801570cba57ce)), closes [#450](https://github.com/Sekai-World/sekai-viewer/issues/450)
* :bug: live2d v2 model motions ([edc1377](https://github.com/Sekai-World/sekai-viewer/commits/edc137732f9a3c6285dadbd4f4d3dc98ccd1de11)), closes [#453](https://github.com/Sekai-World/sekai-viewer/issues/453)
* :bug: music category display ([fe1a626](https://github.com/Sekai-World/sekai-viewer/commits/fe1a626e881dc93bd9b06d45a70a8783a35cfa3a)), closes [#448](https://github.com/Sekai-World/sekai-viewer/issues/448)

### [1.7.5](https://github.com/Sekai-World/sekai-viewer/compare/v1.7.4...v1.7.5) (2023-10-24)


### Bug Fixes

* :bug: asset-viewer cannot list root folder ([79eb3f1](https://github.com/Sekai-World/sekai-viewer/commits/79eb3f197af4912083f24bf9c8439e278c80cf06))

### [1.7.4](https://github.com/Sekai-World/sekai-viewer/compare/v1.7.3...v1.7.4) (2023-07-08)


### Bug Fixes

* :bug: virtual live detail crash ([e65fba9](https://github.com/Sekai-World/sekai-viewer/commits/e65fba96c41713009cfa4456aca9e3f53363f91a))

### [1.7.3](https://github.com/Sekai-World/sekai-viewer/compare/v1.7.2...v1.7.3) (2023-05-21)


### Features

* :sparkles: process compact json data ([3818ae9](https://github.com/Sekai-World/sekai-viewer/commits/3818ae9be0518af20aa32b40da62cd6793a6a005))


### Bug Fixes

* :bug: event honor badge display for TW and KR servers ([df0b862](https://github.com/Sekai-World/sekai-viewer/commits/df0b862b657ba8f51b14472a0942002725669a54))


### Refactors

* :clown_face: passthrough current-event request ([dee2e8d](https://github.com/Sekai-World/sekai-viewer/commits/dee2e8d0a732e0be195416960d59971fb577e65b))

### [1.7.2](https://github.com/Sekai-World/sekai-viewer/compare/v1.7.1...v1.7.2) (2023-05-18)


### Features

* :clown_face: mock sekai profile update ([2dab17c](https://github.com/Sekai-World/sekai-viewer/commits/2dab17c043660b5f86e04af96d0384eed4c80825))
* :globe_with_meridians: add ua and kr comics ([1187b64](https://github.com/Sekai-World/sekai-viewer/commits/1187b64be0ddf8630ac0a07b5b74b42c7959f45a))
* :lipstick: add "do filter" button to music list page ([a5a9f65](https://github.com/Sekai-World/sekai-viewer/commits/a5a9f65c7c28c90449d063cc681b254f037f8d1d))
* :sparkles: 2nd anniversary countdown ([a3bee9f](https://github.com/Sekai-World/sekai-viewer/commits/a3bee9fde4b242500f3e779bfd298778a5440a8b))
* **event:** add max bonus to bonus card list ([c1972e4](https://github.com/Sekai-World/sekai-viewer/commits/c1972e4cb96e93181ebf6bf4df4eb2eb7cf62924))
* **event:** card bonus detail list ([a8a3b22](https://github.com/Sekai-World/sekai-viewer/commits/a8a3b228fb29d24817cebcc74ff091ec7069ba3b))


### Bug Fixes

* :bug: add kr unit logos resource url ([c6e5a94](https://github.com/Sekai-World/sekai-viewer/commits/c6e5a94f355221d0749430de57b5c64d55b154f9))
* :bug: add node-modules-polyfill to fix cron problem ([dbd0ed9](https://github.com/Sekai-World/sekai-viewer/commits/dbd0ed98741e807e222065dae944da42f111dbad))
* :bug: close deletion confirm dialog before execution ([98727bc](https://github.com/Sekai-World/sekai-viewer/commits/98727bcf361c15ad1ab3b1f46b5da4049ba0dacd))
* :bug: episode fields deleted by nuverse ([2372d08](https://github.com/Sekai-World/sekai-viewer/commits/2372d087d8502521674450d7d56880f42d6c9c5b))
* :bug: eventMusics only exist in JP server ([e41b575](https://github.com/Sekai-World/sekai-viewer/commits/e41b575f59071eff69142a89a28f359b47ccc419))
* :bug: filter operation upon opening card list page ([5e55157](https://github.com/Sekai-World/sekai-viewer/commits/5e55157c10e8448d7bac85ab0cc58de83d8a54a0))
* :bug: memoize styled components or make them const ([3c8fae3](https://github.com/Sekai-World/sekai-viewer/commits/3c8fae348c694f22e1bd2c2818cb26b34b8689ee))
* :bug: nuverse deleted fields in cardEpisodes ([fbffe33](https://github.com/Sekai-World/sekai-viewer/commits/fbffe3340b8b6dbfc95230d41879b1d080a2f771))
* :bug: rank match honor asset url ([867ae8c](https://github.com/Sekai-World/sekai-viewer/commits/867ae8c572807812de6cf919516038957dedabe8))
* :bug: sekai profile update error ([75b96aa](https://github.com/Sekai-World/sekai-viewer/commits/75b96aa2c9d89d302f4e9b12439858be36545782))
* :bug: sekai profile userid now string ([c47e339](https://github.com/Sekai-World/sekai-viewer/commits/c47e33979aed51f56ac73cbb6c9d75bf2231ede0))
* :bug: story reader respect spoiler switch and region setting ([f2ca4ff](https://github.com/Sekai-World/sekai-viewer/commits/f2ca4ffcad707acf7eda31795e205468bc5620fc))
* :bug: tw and kr server sekai profile not matching ([9518457](https://github.com/Sekai-World/sekai-viewer/commits/95184570415f2fcd69616277a19587f87f917d51))
* :bug: user config in jp sekai profile ([31f3e6b](https://github.com/Sekai-World/sekai-viewer/commits/31f3e6bddc4f2e3a55137b07b933aeed71603c8f))
* :bug: wrongly trimmed short version of songs ([daabecd](https://github.com/Sekai-World/sekai-viewer/commits/daabecd49b39ef609b1c463bc06e6b0105a86976))
* :lipstick: card image position set to relative ([2d6f3d1](https://github.com/Sekai-World/sekai-viewer/commits/2d6f3d189e4ce00c95408dc59a2b12dba02f635c))
* :lipstick: card image style not working ([b3c4212](https://github.com/Sekai-World/sekai-viewer/commits/b3c421288e98fdb7ba39a69c82be7aa9404ec837))
* :lipstick: degree image style not working ([05b856f](https://github.com/Sekai-World/sekai-viewer/commits/05b856ffac554cb54ddb00e1bb4295f3a2a51cf2))
* 403 and CORS problem for Mainland China developer ([f0d4d1d](https://github.com/Sekai-World/sekai-viewer/commits/f0d4d1dda291333219481f768722151b34d97271))
* add missing region param to one useStrapi usage ([b6db0e2](https://github.com/Sekai-World/sekai-viewer/commits/b6db0e2b0f664ca0881758447ecfb89f86d4b048))
* add null checks for event tracker ([9d38e2c](https://github.com/Sekai-World/sekai-viewer/commits/9d38e2cce18ba75648b1270d72701f09f41e9675))
* enhance skill ([3245a42](https://github.com/Sekai-World/sekai-viewer/commits/3245a42284c7a576e6b3eca780c0024ca4e3a598))
* **event:** more bonus characters after first anniversary ([56b7919](https://github.com/Sekai-World/sekai-viewer/commits/56b7919b64f9efd35c20589c356940b851d0b458))
* jp server music note count field rename ([73b1228](https://github.com/Sekai-World/sekai-viewer/commits/73b12280946ee88244368c478809c3f752022ab3))


### Refactors

* :bento: update anniversary banner to 2nd ([3d6e5de](https://github.com/Sekai-World/sekai-viewer/commits/3d6e5decd581537bd18faceac4dfebc6407ff477))
* :fire: remove china mainland urls ([7a9dba2](https://github.com/Sekai-World/sekai-viewer/commits/7a9dba22ff0ad89444f6e247afa50e0ca6d7e0b8))
* :fire: remove unused console log ([69471f8](https://github.com/Sekai-World/sekai-viewer/commits/69471f85c33269e5c6b3b58d61a7eab023a42e86))
* :fire: unnecessary filter option on stamp list page ([c3fce73](https://github.com/Sekai-World/sekai-viewer/commits/c3fce730d8e4723a3989fd5c0747d02d634171b5))
* :fire: unused console log ([7e3a479](https://github.com/Sekai-World/sekai-viewer/commits/7e3a4799e7af80dba1ca3381d25c436e9c870cae))
* :lipstick: add missing margin bottom to list ([7286539](https://github.com/Sekai-World/sekai-viewer/commits/728653980aeab2b59743e5bd6d7684da075ac39d))
* :lipstick: auto collapse filter after applying ([22e0f25](https://github.com/Sekai-World/sekai-viewer/commits/22e0f25e84eee719e4d89ad5a8cf3861fe87f826))
* :lipstick: unify all toggle button style ([f1dc202](https://github.com/Sekai-World/sekai-viewer/commits/f1dc202746d062f8138d3364f8a22ed69a0598bc))
* :recycle: convert common styles to styled components ([c2cda9d](https://github.com/Sekai-World/sekai-viewer/commits/c2cda9dd8f84bc00f41c521121da07273cd7c36f))
* :recycle: filterOpen -> filterOpened ([0ad1850](https://github.com/Sekai-World/sekai-viewer/commits/0ad1850eba92b5defd455618ddce1440ea98d32f))
* :recycle: remove all usage of @mui/styles and use styled components and sx props ([073025a](https://github.com/Sekai-World/sekai-viewer/commits/073025a4f9867c2e08a3157a8aa1b9c90ba3ad99))

### [1.7.1](https://github.com/Sekai-World/sekai-viewer/compare/v1.7.0...v1.7.1) (2023-01-14)


### Bug Fixes

* :bug: remove country detection in settings page ([5fc211f](https://github.com/Sekai-World/sekai-viewer/commits/5fc211f1967ab48d24fe34366df206e161e9da80))

## [1.7.0](https://github.com/Sekai-World/sekai-viewer/compare/v1.6.11...v1.7.0) (2023-01-14)


### Bug Fixes

* :bug: sekai profile userid now string ([163a23d](https://github.com/Sekai-World/sekai-viewer/commits/163a23d2d91e8600ebf66ecd7864ac172aa78221))


### Refactors

* :fire: remove china mainland urls ([d4d3a90](https://github.com/Sekai-World/sekai-viewer/commits/d4d3a90c338f667d44dff216f3495d41c9767329))

### [1.6.11](https://github.com/Sekai-World/sekai-viewer/compare/v1.6.10...v1.6.11) (2023-01-13)


### Bug Fixes

* :bug: user config in jp sekai profile ([f3d7728](https://github.com/Sekai-World/sekai-viewer/commits/f3d7728911d2f4baa0ac19d0962cb1c43fa76e29))

### [1.6.10](https://github.com/Sekai-World/sekai-viewer/compare/v1.6.9...v1.6.10) (2022-12-21)


### Bug Fixes

* jp server music note count field rename ([a08398d](https://github.com/Sekai-World/sekai-viewer/commits/a08398d772db2f6715ce0e6369dd13e5a07777c2))

### [1.6.9](https://github.com/Sekai-World/sekai-viewer/compare/v1.6.8...v1.6.9) (2022-12-18)


### Bug Fixes

* :bug: sekai profile update error ([e0174cd](https://github.com/Sekai-World/sekai-viewer/commits/e0174cd2d4bad4fc4cc9bfec0f2c8023e88554f5))
* add missing region param to one useStrapi usage ([544bd37](https://github.com/Sekai-World/sekai-viewer/commits/544bd3725562b78171753e834ec6f966970d568f))

### [1.6.8](https://github.com/Sekai-World/sekai-viewer/compare/v1.6.7...v1.6.8) (2022-11-01)


### Bug Fixes

* :bug: tw and kr server sekai profile not matching ([19badb6](https://github.com/Sekai-World/sekai-viewer/commits/19badb64c27d01e57dd38734a7944b321992c93e))
* enhance skill ([b171341](https://github.com/Sekai-World/sekai-viewer/commits/b17134143f21035799c17d49514b979638a2727b))

### [1.6.7](https://github.com/Sekai-World/sekai-viewer/compare/v1.6.6...v1.6.7) (2022-10-24)


### Features

* **event:** add max bonus to bonus card list ([0fd596a](https://github.com/Sekai-World/sekai-viewer/commits/0fd596a67ca3027d7da2dd798e7210acb3e1f666))
* **event:** card bonus detail list ([d184acf](https://github.com/Sekai-World/sekai-viewer/commits/d184acfda0e119ea83963601c860527a21794aa0))


### Bug Fixes

* :bug: wrongly trimmed short version of songs ([1ec2456](https://github.com/Sekai-World/sekai-viewer/commits/1ec245645f4c60d63b5cff3b876cbee1ac73e1f8))
* 403 and CORS problem for Mainland China developer ([2ad3b63](https://github.com/Sekai-World/sekai-viewer/commits/2ad3b63438dc3a1b8c23872e7e34039b0f383d20))
* **event:** more bonus characters after first anniversary ([061fd2a](https://github.com/Sekai-World/sekai-viewer/commits/061fd2a601838a69d8766d094b8131b2d07d36a2))

### [1.6.6](https://github.com/Sekai-World/sekai-viewer/compare/v1.6.5...v1.6.6) (2022-10-10)


### Bug Fixes

* :bug: add kr unit logos resource url ([1d751e2](https://github.com/Sekai-World/sekai-viewer/commits/1d751e2f26b2ac35c09470e32720d9a2680a8cfe))
* :bug: story reader respect spoiler switch and region setting ([3bf570d](https://github.com/Sekai-World/sekai-viewer/commits/3bf570d766e27bee52b641376de297ee90e5ccb7))

### [1.6.5](https://github.com/Sekai-World/sekai-viewer/compare/v1.6.4...v1.6.5) (2022-10-04)


### Features

* :lipstick: add "do filter" button to music list page ([73139f6](https://github.com/Sekai-World/sekai-viewer/commits/73139f600d3ad8c0361dd01fb33b7f9a74a2bc8c))


### Bug Fixes

* :bug: filter operation upon opening card list page ([af38e0e](https://github.com/Sekai-World/sekai-viewer/commits/af38e0ee5805a6eba6daae233fcd9714fb765b79))


### Refactors

* :fire: unnecessary filter option on stamp list page ([dd23d9b](https://github.com/Sekai-World/sekai-viewer/commits/dd23d9bf78516b2d3e5d7306e64a647f2e419f76))
* :fire: unused console log ([632abf3](https://github.com/Sekai-World/sekai-viewer/commits/632abf3f0863bb21fcf6097435141c930bddd48a))
* :recycle: filterOpen -> filterOpened ([2c2db70](https://github.com/Sekai-World/sekai-viewer/commits/2c2db707e5f338cebc722d3b92947d28f25a4f84))

### [1.6.4](https://github.com/Sekai-World/sekai-viewer/compare/v1.6.3...v1.6.4) (2022-09-29)


### Bug Fixes

* :lipstick: card image position set to relative ([d05cc2b](https://github.com/Sekai-World/sekai-viewer/commits/d05cc2b75b85bb625c87861586db51569b24909b))


### Refactors

* :lipstick: add missing margin bottom to list ([529790c](https://github.com/Sekai-World/sekai-viewer/commits/529790c8b00d30976b6e1283296c71a99ec4cafb))
* :lipstick: unify all toggle button style ([a2bc804](https://github.com/Sekai-World/sekai-viewer/commits/a2bc8044275c17adee4af68ea04e4ed1ce692875))

### [1.6.3](https://github.com/Sekai-World/sekai-viewer/compare/v1.6.2...v1.6.3) (2022-09-29)


### Refactors

* :bento: update anniversary banner to 2nd ([df89b23](https://github.com/Sekai-World/sekai-viewer/commits/df89b23136afb21ee36345bed6e1f900371a1d9a))
* :lipstick: auto collapse filter after applying ([f4a64cd](https://github.com/Sekai-World/sekai-viewer/commits/f4a64cd94a2579ddee7bf35d3727431b3501d7f9))

### [1.6.2](https://github.com/Sekai-World/sekai-viewer/compare/v1.6.1...v1.6.2) (2022-09-28)


### Bug Fixes

* :bug: memoize styled components or make them const ([7e376db](https://github.com/Sekai-World/sekai-viewer/commits/7e376dba393e1ae97b31cc39fc1ab950f3af606c))


### Refactors

* :fire: remove unused console log ([48c4d4f](https://github.com/Sekai-World/sekai-viewer/commits/48c4d4fafa34a0c6d4c871da6aab63d32a580923))

### [1.6.1](https://github.com/Sekai-World/sekai-viewer/compare/v1.6.0...v1.6.1) (2022-09-27)


### Features

* :globe_with_meridians: add ua and kr comics ([95a1c46](https://github.com/Sekai-World/sekai-viewer/commits/95a1c461847f9ea8a19c808645f502402bf422f3))


### Bug Fixes

* :lipstick: card image style not working ([324f698](https://github.com/Sekai-World/sekai-viewer/commits/324f698fe895698f1f6572e967a2d370ce32c70e))
* :lipstick: degree image style not working ([99da7a7](https://github.com/Sekai-World/sekai-viewer/commits/99da7a79b54063e1936ab33640a4190d2b94bd65))

## [1.6.0](https://github.com/Sekai-World/sekai-viewer/compare/v1.5.3...v1.6.0) (2022-09-27)


### Refactors

* :recycle: convert common styles to styled components ([1929516](https://github.com/Sekai-World/sekai-viewer/commits/19295168433872b6ec1f25ccb5e8f66a37847698))
* :recycle: remove all usage of @mui/styles and use styled components and sx props ([1a8c51e](https://github.com/Sekai-World/sekai-viewer/commits/1a8c51eb0c20eae13c37d09bc2849c1a69ff64d6))

### [1.5.3](https://github.com/Sekai-World/sekai-viewer/compare/v1.5.2...v1.5.3) (2022-09-23)


### Bug Fixes

* :bug: eventMusics only exist in JP server ([e86cc84](https://github.com/Sekai-World/sekai-viewer/commits/e86cc8458b383bea6799ea8c2d4b705bd514ff5d))

### [1.5.2](https://github.com/Sekai-World/sekai-viewer/compare/v1.5.1...v1.5.2) (2022-09-22)


### Bug Fixes

* :bug: episode fields deleted by nuverse ([12aab08](https://github.com/Sekai-World/sekai-viewer/commits/12aab08a188b523e75b23a1ef71abbe7d9818afd))
* :bug: nuverse deleted fields in cardEpisodes ([7836f90](https://github.com/Sekai-World/sekai-viewer/commits/7836f9074396139c0c51ac1bc7d41ebb23facc49))
* :bug: rank match honor asset url ([1883fca](https://github.com/Sekai-World/sekai-viewer/commits/1883fca275aaf7f0e28b3e80fa757aa14b552f88))

### [1.5.1](https://github.com/Sekai-World/sekai-viewer/compare/v1.5.0...v1.5.1) (2022-09-21)


### Features

* :bento: add sub degree frame ([d067bc5](https://github.com/Sekai-World/sekai-viewer/commits/d067bc5b77a982ad81e81dac88be6cae59fed229))
* :sparkles: 2nd anniversary countdown ([66c721c](https://github.com/Sekai-World/sekai-viewer/commits/66c721c490537c72ad6e05535c95b81005581eb2))
* :sparkles: bonds honor badge ([f09e488](https://github.com/Sekai-World/sekai-viewer/commits/f09e48830a51eb8cd6f9a257d8f6cd4e5a4ab47f))
* **event:** :sparkles: show new user profile honors ([0a4e822](https://github.com/Sekai-World/sekai-viewer/commits/0a4e822651971fb054f23e76c738988d0da9f411))
* **sekai-viewer:** withlist entry point ([58b3723](https://github.com/Sekai-World/sekai-viewer/commits/58b37234d9789da89f103dd44860773a7abc9f4e))
* **story:** :sparkles: add special stories to story reader ([511fc3b](https://github.com/Sekai-World/sekai-viewer/commits/511fc3b4d72c77cfacf4bcb28a4db8f9b8c86de9))


### Bug Fixes

* :bug: add node-modules-polyfill to fix cron problem ([b53a82a](https://github.com/Sekai-World/sekai-viewer/commits/b53a82a838c898b2715db6dce1b1249adcf69b24))
* :bug: further fixing sekai data type annotation ([ebfcf37](https://github.com/Sekai-World/sekai-viewer/commits/ebfcf37fe4e92bdc56013d39b9a06db195343f4a))
* :lipstick: degree sub style improvements ([7949b09](https://github.com/Sekai-World/sekai-viewer/commits/7949b095010e9e9c4003fc4f8ca7b29954aa77c6))
* **card:** :bug: correctly process card detail without side stories ([5fc4e7f](https://github.com/Sekai-World/sekai-viewer/commits/5fc4e7ffa1e68950f0bbf279d2cac94b1a56f065))
* **card:** :bug: really fix the empty list problem ([7c4fe58](https://github.com/Sekai-World/sekai-viewer/commits/7c4fe581118379efbd1cd2dd77be9b10aa9d9a00))
* collab area icons and voice ([3cd3988](https://github.com/Sekai-World/sekai-viewer/commits/3cd39888e174f540e1c12f6d2126112f627b834c))
* **event:** :bug: en server event tracker shows jp result after event ends ([98e2b2e](https://github.com/Sekai-World/sekai-viewer/commits/98e2b2e80160b00a2dffa3c5b465c527a2dd1496))
* **gacha:** :bug: gacha detail card rate becomes NaN ([fba9e6a](https://github.com/Sekai-World/sekai-viewer/commits/fba9e6af351aea1c4de88d29f5d39a446ce8aeb5))
* **home:** :bug: game news spoiler filter, en url fix ([ca40eb8](https://github.com/Sekai-World/sekai-viewer/commits/ca40eb8fb31dbea0b40d72e8f0d6212c40c9d0c6))
* **home:** :bug: service worker reload prompt wrong location ([6bcb76d](https://github.com/Sekai-World/sekai-viewer/commits/6bcb76d7b215456e420630d5a4900fb7f4e1954e))
* **live2d:** :bug: jp clb model motion base url ([255ed13](https://github.com/Sekai-World/sekai-viewer/commits/255ed13e94d1c6cb5d86ee96ce97ebb82523b7b6))
* **live2d:** :lipstick: fit wide screen mobile device ([17f0c12](https://github.com/Sekai-World/sekai-viewer/commits/17f0c120005b92d986c07fce346686be0b0bfc80))
* **story:** :bug: special story wrong voice path ([cc1dcb1](https://github.com/Sekai-World/sekai-viewer/commits/cc1dcb11034ea43234fff7b3926f8cf2e17dd7c9))
* **tools:** :bug: event pt calc wrong bonus rate ([63daf95](https://github.com/Sekai-World/sekai-viewer/commits/63daf95488bdba9ff5cdab532350a49b727574a2)), closes [#353](https://github.com/Sekai-World/sekai-viewer/issues/353)
* **user:** :lipstick: bonds degree badge reverse ([8cb3942](https://github.com/Sekai-World/sekai-viewer/commits/8cb3942e25f04401141d054d22b5612ee4939132))
* **user:** sekai profile cards teams story unlock type fix ([12c42e2](https://github.com/Sekai-World/sekai-viewer/commits/12c42e2d963e1db79d0854a2c13523c7db3b843a))


### Refactors

* :lipstick: normal degree image width ([f9a386d](https://github.com/Sekai-World/sekai-viewer/commits/f9a386d10709e5aac260ba76b2815bbe5e621e73))
* :recycle: remove redundant codes ([d8af11d](https://github.com/Sekai-World/sekai-viewer/commits/d8af11d07dcddf8bc1de3a7e9227f95b0342d5d3))
* **event:** :lipstick: make event tracker table looks better ([3fcd8f1](https://github.com/Sekai-World/sekai-viewer/commits/3fcd8f15f1e4eeb816d7f6a3bc616329b6c212bb))
* **gacha:** filter not really opened en gachas ([2507188](https://github.com/Sekai-World/sekai-viewer/commits/2507188285630190ca8bcf93592cf1f4c3aa48ff))
* **live2d:** :lipstick: live2d toolbar and display area padding remove ([77f3434](https://github.com/Sekai-World/sekai-viewer/commits/77f3434f772e013e08735692b3627d5d224dd37b))
* open external link in new instead of current page ([e9492bd](https://github.com/Sekai-World/sekai-viewer/commits/e9492bdadbd817c35572547139b1d2bfd131587e))
* **user:** :ambulance: sekai new profile structure (user honors) ([6e1c230](https://github.com/Sekai-World/sekai-viewer/commits/6e1c230d2895570e73f70fa30efb9fa8450609c1))
* **user:** :lipstick: style fix ([3a08e01](https://github.com/Sekai-World/sekai-viewer/commits/3a08e0160aa6b66117a33ebfa35756d7460d70c6))

## [1.5.0](https://github.com/Sekai-World/sekai-viewer/compare/v1.4.3...v1.5.0) (2022-09-21)


### Features

* :clown_face: add mock handlers for user system ([56c4fc0](https://github.com/Sekai-World/sekai-viewer/commits/56c4fc05f59805e501bd62ce75e8302a3dbe6ac2))
* :clown_face: add mock handlers for user system ([8a08d74](https://github.com/Sekai-World/sekai-viewer/commits/8a08d743472e9f8eb9e107f97ba96b71aa5c3408))
* :clown_face: add msw to browser env ([0453602](https://github.com/Sekai-World/sekai-viewer/commits/04536025018f842e8bf3f518d87272b859c4b121))
* :clown_face: add msw to browser env ([1e26864](https://github.com/Sekai-World/sekai-viewer/commits/1e26864887c8796c382023653e85ce56dbf5a120))
* :sparkles: add newly written song for events ([23ce998](https://github.com/Sekai-World/sekai-viewer/commits/23ce9988efef18c1c004521e2f681c4554dc0e2b))
* :sparkles: add newly written song for events ([c0c9ffe](https://github.com/Sekai-World/sekai-viewer/commits/c0c9ffe7bd536e1a115fc6edd1c4bf2726d4ed30))
* :sparkles: add sorting to honor and mission list ([4dc4aed](https://github.com/Sekai-World/sekai-viewer/commits/4dc4aed4ca7e00e402a48997ab0ad1e7702c931e))
* :sparkles: add sorting to honor and mission list ([172a545](https://github.com/Sekai-World/sekai-viewer/commits/172a54506e6042e6d7518b2a3b98cc35dea029f8))


### Bug Fixes

* :lipstick: avoid character rank ellipsis ([c812190](https://github.com/Sekai-World/sekai-viewer/commits/c812190c7feeb30c63437a1345a8ff4381394158))
* :lipstick: avoid character rank ellipsis ([83ca262](https://github.com/Sekai-World/sekai-viewer/commits/83ca2623b0beeb4b6f33b2be74c36c2010934570))
* :lipstick: not centered material icon and quantity text ([8ff8efa](https://github.com/Sekai-World/sekai-viewer/commits/8ff8efa1b864df783408824e300e71e0723a7db2))
* :lipstick: not centered material icon and quantity text ([e9be4d5](https://github.com/Sekai-World/sekai-viewer/commits/e9be4d5e907614d0dc8db06b0ea2f7059eada8d8))
* **score:** multiroom player skill calculation ([3efca62](https://github.com/Sekai-World/sekai-viewer/commits/3efca62a8fdf544ee09cefc4471bc0463bfce608))


### Refactors

* :clown_face: add msw to react ([ba65860](https://github.com/Sekai-World/sekai-viewer/commits/ba65860329737a70c79869eb969bb5f4a40f489f))
* :clown_face: add msw to react ([8ba6ff0](https://github.com/Sekai-World/sekai-viewer/commits/8ba6ff014702cb23e6f1838bb8f6c0eb61ff0665))
* :truck: use storage.sekai.best instead of minio.dnaroma.eu ([cf60f6c](https://github.com/Sekai-World/sekai-viewer/commits/cf60f6cb592da59e67bf404c990c3bf35b28f98a))

### [1.4.3](https://github.com/Sekai-World/sekai-viewer/compare/v1.4.2...v1.4.3) (2022-08-17)

### [1.4.2](https://github.com/Sekai-World/sekai-viewer/compare/v1.4.1...v1.4.2) (2022-08-16)


### Refactors

* :truck: use storage.sekai.best instead of minio.dnaroma.eu ([bb35e96](https://github.com/Sekai-World/sekai-viewer/commits/bb35e966fefe555a720c9b3a8c58c056286059b6))

### [1.4.1](https://github.com/Sekai-World/sekai-viewer/compare/v1.4.0...v1.4.1) (2022-06-01)


### Features

* **home:** :memo: add disclaimer ([7f2a569](https://github.com/Sekai-World/sekai-viewer/commits/7f2a5694f5a02cb31d81606e37b02a3b0852773f))

## [1.4.0](https://github.com/Sekai-World/sekai-viewer/compare/v1.3.2...v1.4.0) (2022-05-31)


### Features

* add korean server ([474a13a](https://github.com/Sekai-World/sekai-viewer/commits/474a13aa2c0b53a890e922b91ddc6b70def8e28a))
* **gacha:** :sparkles: gacha fetch images from remote list ([d82005a](https://github.com/Sekai-World/sekai-viewer/commits/d82005ab481b13b3ea34c2c62ae45da8c498b38f))


### Bug Fixes

* **card:** :bug: birthday card stats are NaN ([7709d90](https://github.com/Sekai-World/sekai-viewer/commits/7709d901197748949b9f2c4b5bb2fd9a3acbcc8c))


### Refactors

* abandon b2 storage ([db610a7](https://github.com/Sekai-World/sekai-viewer/commits/db610a7659fdeb38d1aadf6e6a01003f35ddfd29))
* change webp-hero implementation ([658d106](https://github.com/Sekai-World/sekai-viewer/commits/658d106b4d085ae0ad1f8ee3276dba1e92ee0737))
* index description change ([818d248](https://github.com/Sekai-World/sekai-viewer/commits/818d2485528f0d35bd36843b16ee1615871b09e5))

### [1.3.2](https://github.com/Sekai-World/sekai-viewer/compare/v1.3.1...v1.3.2) (2022-04-30)


### Bug Fixes

* **tools:** :bug: filter cards modal in team builder may cause unwanted updates ([5e477b1](https://github.com/Sekai-World/sekai-viewer/commits/5e477b13e61d7ba220dd665bec1f27e1d51d3f10))

### [1.3.1](https://github.com/Sekai-World/sekai-viewer/compare/v1.3.0...v1.3.1) (2022-04-30)


### Bug Fixes

* **card:** :bug: check skill before displaying it ([f66ddc9](https://github.com/Sekai-World/sekai-viewer/commits/f66ddc90e932b4a65353d5706c6cb9751bebf54b))

## [1.3.0](https://github.com/Sekai-World/sekai-viewer/compare/v1.2.12...v1.3.0) (2022-04-30)


### Features

* :sparkles: asset viewer now supports different regions ([13c48b6](https://github.com/Sekai-World/sekai-viewer/commits/13c48b6aa1f846fa6e0a54e1babd015e84726c57))


### Bug Fixes

* **event:** :ambulance: load history data from database ([01ed396](https://github.com/Sekai-World/sekai-viewer/commits/01ed396a0af97b3baa44623a3568a88ea9efc516))
* **event:** :bug: record event data on other servers ([174974e](https://github.com/Sekai-World/sekai-viewer/commits/174974e1ecc2594b9bcd1038f619dd90007bd9f3))


### Refactors

* :recycle: url from env replaced by urls from utilities ([6ffe2de](https://github.com/Sekai-World/sekai-viewer/commits/6ffe2de23e4aed2d06658c4038fec737080f623d))

### [1.2.12](https://github.com/Sekai-World/sekai-viewer/compare/v1.2.11...v1.2.12) (2022-04-11)


### Bug Fixes

* **user:** :bug: removed already existed user cards from filter list, minor bugs fixed ([b8b88c1](https://github.com/Sekai-World/sekai-viewer/commits/b8b88c120f72056e14ef4242d74b1f1a59054a5f))
* **user:** :bug: user card list sort by rarity ([48a74f3](https://github.com/Sekai-World/sekai-viewer/commits/48a74f3747b9137cd462c4b22ca079091c6f97ea))

### [1.2.11](https://github.com/Sekai-World/sekai-viewer/compare/v1.2.10...v1.2.11) (2022-04-05)


### Bug Fixes

* **story:** :bug: failed to show story lines due to missing mob character entries ([49f0f01](https://github.com/Sekai-World/sekai-viewer/commits/49f0f019009c074063d6a34a9ccfa79d00b9c864))

### [1.2.10](https://github.com/Sekai-World/sekai-viewer/compare/v1.2.9...v1.2.10) (2022-04-05)


### Features

* add support for custom font's for each language + Add Thai fonts support ([6b59f5c](https://github.com/Sekai-World/sekai-viewer/commits/6b59f5c317c73937a87b3e514045681d7c47aa4d))


### Bug Fixes

* :bug: useCallback missing deps in sekai user card list ([ecbced3](https://github.com/Sekai-World/sekai-viewer/commits/ecbced3a6d735afac4877f0181c9c876e0283c3d))
* **tools:** :bug: filter card by rarity in jp server ([18e9ca2](https://github.com/Sekai-World/sekai-viewer/commits/18e9ca2db6a4f21d7d46a56910743910bd3c16ee))


### Refactors

* :lipstick: font family order change ([5152cf4](https://github.com/Sekai-World/sekai-viewer/commits/5152cf456d80c6913637a1c27a665ef9c9e49eea))
* :recycle: use china friendly url ([a21dbcb](https://github.com/Sekai-World/sekai-viewer/commits/a21dbcbf52b05bf19ad55b6e8415d2c36cf63125))
* :rotating_light: remove unused codes ([f6d4c68](https://github.com/Sekai-World/sekai-viewer/commits/f6d4c6870fe054394d6bc7b0b655341b9d46e5c1))
* :truck: move comics to separate bucket ([eb33dbd](https://github.com/Sekai-World/sekai-viewer/commits/eb33dbddcd379646187a62b44229013702a6cc96))
* :truck: move fonts to utils ([469ef58](https://github.com/Sekai-World/sekai-viewer/commits/469ef58f3efd55d6b2d0ed9106540bc882212ed6))
* :truck: move music charts to separate bucket ([440e9cc](https://github.com/Sekai-World/sekai-viewer/commits/440e9cc182e3897b3ba77d7040d8620935233434))
* change how the web decides which fonts to use ([5f95af0](https://github.com/Sekai-World/sekai-viewer/commits/5f95af09e8315c5bb35755ef68ed4a6e66eb2131))
* import fonts from font-face instead of <link> ([864cdfb](https://github.com/Sekai-World/sekai-viewer/commits/864cdfbd945e0b0aba103b559e67a8371b132fcc))

### [1.2.9](https://github.com/Sekai-World/sekai-viewer/compare/v1.2.8...v1.2.9) (2022-03-11)


### Features

* :sparkles: add costume 3d thumbnails ([cf0d7cf](https://github.com/Sekai-World/sekai-viewer/commits/cf0d7cf4010a8db4724e6a89fe70f63fb315fba2))
* **card:** :sparkles: add master rank and rewards to card detail page ([c40a168](https://github.com/Sekai-World/sekai-viewer/commits/c40a16832cd8b4d3e0aafe4bfe7a122958d72a8f))


### Bug Fixes

* **music:** :bug: wrong music release condition ([538ec93](https://github.com/Sekai-World/sekai-viewer/commits/538ec93db229db16d04037a543fca31dab5c7cc4))


### Refactors

* :fire: remove ad on home and event tracker ([79d6640](https://github.com/Sekai-World/sekai-viewer/commits/79d66409f78c99caa0fe97446aa00dfc768cf27e))
* :lipstick: material icon style fix ([084fa46](https://github.com/Sekai-World/sekai-viewer/commits/084fa4601cd775622fd11dce66517e3d9834034f))

### [1.2.8](https://github.com/Sekai-World/sekai-viewer/compare/v1.2.7...v1.2.8) (2022-02-26)


### Bug Fixes

* **card:** :bug: rarity field is removed in JP server ([aa6f565](https://github.com/Sekai-World/sekai-viewer/commits/aa6f565c5df99a080fb94fdbbf02c536d3f9b99e)), closes [#373](https://github.com/Sekai-World/sekai-viewer/issues/373)

### [1.2.7](https://github.com/Sekai-World/sekai-viewer/compare/v1.2.6...v1.2.7) (2022-02-16)


### Features

* **Home:** add kaito banner ([95db8a2](https://github.com/Sekai-World/sekai-viewer/commits/95db8a23c475fcaa625004278744b6cd46c040c6))

### [1.2.6](https://github.com/Sekai-World/sekai-viewer/compare/v1.2.5...v1.2.6) (2022-01-26)


### Bug Fixes

* **musicRecommend:** scroll-to-top button overlapped with content ([425802e](https://github.com/Sekai-World/sekai-viewer/commits/425802e0e07aba465576a404042f7dc15aab9d12))
* **tools:** :lipstick: make scroll-to-top button not overlapping content in event planner ([f544716](https://github.com/Sekai-World/sekai-viewer/commits/f544716d6b77871a7709752b1fbb11674061bd15))


### Refactors

* **tools:** :rotating_light: remove warnings in music recommender ([f7ae04c](https://github.com/Sekai-World/sekai-viewer/commits/f7ae04caa6b7b1f5747ee8d4303cc9dba1f527d8))

### [1.2.5](https://github.com/Sekai-World/sekai-viewer/compare/v1.2.4...v1.2.5) (2022-01-16)


### Features

* **card:** :sparkles: add correlating event title entry ([3397098](https://github.com/Sekai-World/sekai-viewer/commits/3397098aa98b73ee27c3260e558561618f410c9f)), closes [#361](https://github.com/Sekai-World/sekai-viewer/issues/361)
* **cards:** add link to corr event detail page ([eea440a](https://github.com/Sekai-World/sekai-viewer/commits/eea440a4ebdd523ec2870e314fc678c3ab1f8278))


### Bug Fixes

* **user:** :bug: wrong jwt token set function usage ([d235efd](https://github.com/Sekai-World/sekai-viewer/commits/d235efd641d3d4aae9d14fc23b16c13bb3da146f))

### [1.2.4](https://github.com/Sekai-World/sekai-viewer/compare/v1.2.3...v1.2.4) (2021-12-31)


### Bug Fixes

* **home:** :bug: countdown time bug ([e7754b9](https://github.com/Sekai-World/sekai-viewer/commits/e7754b90d4069853d7871de733e20f6f952e1ce2))

### [1.2.3](https://github.com/Sekai-World/sekai-viewer/compare/v1.2.2...v1.2.3) (2021-12-31)


### Refactors

* **home:** :lipstick: new banners ([6cc93f9](https://github.com/Sekai-World/sekai-viewer/commits/6cc93f90420dd67347a1c2ca7ecaaafbc7809cf2))

### [1.2.2](https://github.com/Sekai-World/sekai-viewer/compare/v1.2.1...v1.2.2) (2021-12-29)


### Bug Fixes

* **user:** :ambulance: fix sekai profile type def ([65a6393](https://github.com/Sekai-World/sekai-viewer/commits/65a63935fb033ef095605510b741d8b601529d97))

### [1.2.1](https://github.com/Sekai-World/sekai-viewer/compare/v1.2.0...v1.2.1) (2021-12-29)


### Bug Fixes

* **home:** :bug: service worker reload prompt wrong location ([44e83ad](https://github.com/Sekai-World/sekai-viewer/commits/44e83add65905526eb9ec343bd05c7044e473da1))
* **tools:** :bug: event pt calc wrong bonus rate ([2240434](https://github.com/Sekai-World/sekai-viewer/commits/2240434226c2e6863b23e3c7cc5290dce11d88d2)), closes [#353](https://github.com/Sekai-World/sekai-viewer/issues/353)

## [1.2.0](https://github.com/Sekai-World/sekai-viewer/compare/v1.1.8...v1.2.0) (2021-12-28)


### Features

* :sparkles: bonds honor badge ([e8ab6e1](https://github.com/Sekai-World/sekai-viewer/commits/e8ab6e12dc2168bef87bb3efe3c032ea805beb50))
* **event:** :sparkles: show new user profile honors ([8311854](https://github.com/Sekai-World/sekai-viewer/commits/83118540d00db9dda7ea85ad4f5ddb93d0c4473f))
* **sekai-viewer:** withlist entry point ([650be2b](https://github.com/Sekai-World/sekai-viewer/commits/650be2b67851214fa8f8bc907d3671a24f5f3ff9))


### Bug Fixes

* :lipstick: degree sub style improvements ([58feaa1](https://github.com/Sekai-World/sekai-viewer/commits/58feaa1f74e9eca38305a5a19a39f4e7396b2938))
* **user:** :lipstick: bonds degree badge reverse ([ce95020](https://github.com/Sekai-World/sekai-viewer/commits/ce950201f1a3a09af472fe7f8875a797c1979321))


### Refactors

* :lipstick: normal degree image width ([1935e89](https://github.com/Sekai-World/sekai-viewer/commits/1935e89e902bacec42a043ad3530d80a72eafd3c))
* open external link in new instead of current page ([c549dc2](https://github.com/Sekai-World/sekai-viewer/commits/c549dc27a9a5843d459505285e8c4fee91065c1b))
* **user:** :ambulance: sekai new profile structure (user honors) ([7dbeabf](https://github.com/Sekai-World/sekai-viewer/commits/7dbeabf9c203c7cf5f1c34ea09c42c0f11390e89))

### [1.1.8](https://github.com/Sekai-World/sekai-viewer/compare/v1.1.7...v1.1.8) (2021-12-23)


### Bug Fixes

* :bug: further fixing sekai data type annotation ([f6b7515](https://github.com/Sekai-World/sekai-viewer/commits/f6b7515d8bba4b56033ca92222993ccbcf5eceae))
* **home:** :bug: game news spoiler filter, en url fix ([0574068](https://github.com/Sekai-World/sekai-viewer/commits/05740682b5b048229a73183eb6f03bacdaa76061))


### Refactors

* **live2d:** :lipstick: live2d toolbar and display area padding remove ([dd67c4d](https://github.com/Sekai-World/sekai-viewer/commits/dd67c4d7920c190e3419fcb5a285cb5dfc1b764e))

### [1.1.7](https://github.com/Sekai-World/sekai-viewer/compare/v1.1.6...v1.1.7) (2021-12-15)


### Features

* :bento: add sub degree frame ([42d638e](https://github.com/Sekai-World/sekai-viewer/commits/42d638e39adadc4effd58773717dedff1f710a64))


### Bug Fixes

* **event:** :bug: en server event tracker shows jp result after event ends ([d01eaa8](https://github.com/Sekai-World/sekai-viewer/commits/d01eaa86d1decae4d6411d3883e0f763a5f5dc0e))


### Refactors

* **event:** :lipstick: make event tracker table looks better ([1e90fe3](https://github.com/Sekai-World/sekai-viewer/commits/1e90fe363ec3698d4ff532a51285a4ea9a06488c))
* **user:** :lipstick: style fix ([257d083](https://github.com/Sekai-World/sekai-viewer/commits/257d083ebe3dd46c1348eea63cc9ed9b4fa3f1c3))

### [1.1.6](https://github.com/Sekai-World/sekai-viewer/compare/v1.1.5...v1.1.6) (2021-12-14)


### Bug Fixes

* collab area icons and voice ([86b19ad](https://github.com/Sekai-World/sekai-viewer/commits/86b19ada0f3b24b70e245ff53dc46a9d52a4f5d4))

### [1.1.5](https://github.com/Sekai-World/sekai-viewer/compare/v1.1.4...v1.1.5) (2021-12-14)


### Bug Fixes

* **user:** sekai profile cards teams story unlock type fix ([b21ca63](https://github.com/Sekai-World/sekai-viewer/commits/b21ca6368ba164968b530cb287b0d8d97e636d33))

### [1.1.4](https://github.com/Sekai-World/sekai-viewer/compare/v1.1.3...v1.1.4) (2021-12-14)


### Bug Fixes

* **card:** :bug: correctly process card detail without side stories ([da132a0](https://github.com/Sekai-World/sekai-viewer/commits/da132a0d1121a186382ee74c0248dcbd0f0d707f))
* **live2d:** :lipstick: fit wide screen mobile device ([b986f09](https://github.com/Sekai-World/sekai-viewer/commits/b986f09caf2a3147757efbd8d28d1e7df72dfa8a))

### [1.1.3](https://github.com/Sekai-World/sekai-viewer/compare/v1.1.2...v1.1.3) (2021-12-14)


### Bug Fixes

* **live2d:** :bug: jp clb model motion base url ([980bbe8](https://github.com/Sekai-World/sekai-viewer/commits/980bbe8ba933b6efca497abcac657024d808202d))

### [1.1.2](https://github.com/Sekai-World/sekai-viewer/compare/v1.1.1...v1.1.2) (2021-12-13)


### Bug Fixes

* **story:** :bug: special story wrong voice path ([8452ead](https://github.com/Sekai-World/sekai-viewer/commits/8452eadb98599c246fe6439f1dee880f30295e27))

### [1.1.1](https://github.com/Sekai-World/sekai-viewer/compare/v1.1.0...v1.1.1) (2021-12-13)


### Features

* **story:** :sparkles: add special stories to story reader ([68e1b1d](https://github.com/Sekai-World/sekai-viewer/commits/68e1b1dfccc5aa9c0376b975b0f8c0027c5f093d))


### Bug Fixes

* **card:** :bug: really fix the empty list problem ([842b2cb](https://github.com/Sekai-World/sekai-viewer/commits/842b2cb603a96c5239d577c3178350bb241a6d9e))
* **gacha:** :bug: gacha detail card rate becomes NaN ([024a2a4](https://github.com/Sekai-World/sekai-viewer/commits/024a2a42524a126c979516291fe00bb54ed2e9cb))


### Refactors

* **gacha:** filter not really opened en gachas ([328c3d0](https://github.com/Sekai-World/sekai-viewer/commits/328c3d005ac52c23c496cd54e90fdea5fc693808))

## [1.1.0](https://github.com/Sekai-World/sekai-viewer/compare/v1.0.5...v1.1.0) (2021-12-09)


### Features

* **gacha:** :sparkles: gacha simulator improvement, allow birthday cards ([abd29ab](https://github.com/Sekai-World/sekai-viewer/commits/abd29ab654b274f1a8190ae5d925ce2acb1a9efb))
* **layout:** :lipstick: allow material icons to have mini variant ([cde5d6c](https://github.com/Sekai-World/sekai-viewer/commits/cde5d6c5248536b6ae3a2c19dac6dc77067000ea))


### Bug Fixes

* **card:** :bug: empty card list because of race condition ([baedd13](https://github.com/Sekai-World/sekai-viewer/commits/baedd1332f477ef7744949d65bac8869c2d8adc1))
* **card:** :bug: optional property cardRarityType ([7dbf5c6](https://github.com/Sekai-World/sekai-viewer/commits/7dbf5c60d2b46b3d139d2076c3e148ce5f4079dc))
* **user:** :bug: event record filtering event ([e6c5ebc](https://github.com/Sekai-World/sekai-viewer/commits/e6c5ebcb4150de4b9c6462ee686fee2e2bc95e0a))


### Refactors

* **home:** :zap: split sekai game news table component from home ([6e82f08](https://github.com/Sekai-World/sekai-viewer/commits/6e82f082fe57d18ab8a169643662e833700310ac))

### [1.0.5](https://github.com/Sekai-World/sekai-viewer/compare/v1.0.4...v1.0.5) (2021-12-08)


### Bug Fixes

* **user:** :bug: import card not working for EN and TW ([046c456](https://github.com/Sekai-World/sekai-viewer/commits/046c4569f551900d58279a55aeb1ab0566ece6de))

### [1.0.4](https://github.com/Sekai-World/sekai-viewer/compare/v1.0.3...v1.0.4) (2021-12-08)


### Bug Fixes

* **user:** :bug: sekai profile model definition ([96f20df](https://github.com/Sekai-World/sekai-viewer/commits/96f20dfe89712616b9e67e59cac705c7418fdbbf))


### Refactors

* **user:** verify carousel open state ([98560e3](https://github.com/Sekai-World/sekai-viewer/commits/98560e3dd700a20352031b817a27d9f4aad0ee90))

### [1.0.3](https://github.com/Sekai-World/sekai-viewer/compare/v1.0.2...v1.0.3) (2021-12-08)


### Bug Fixes

* **user:** :bug: forget to set sekai card team map after creation empty one ([542c310](https://github.com/Sekai-World/sekai-viewer/commits/542c31019d32035cf4135fc2724c9179a8813985))

### [1.0.2](https://github.com/Sekai-World/sekai-viewer/compare/v1.0.1...v1.0.2) (2021-12-08)


### Bug Fixes

* **user:** :bug: sekai id binding and other function are not functioning ([8b38ea8](https://github.com/Sekai-World/sekai-viewer/commits/8b38ea8c959ddba7cfeebe08069a4ba008fd7e35))


### Refactors

* **event:** :recycle: use unified sekai event record ([7fe2fe2](https://github.com/Sekai-World/sekai-viewer/commits/7fe2fe2fef1f9b246ba86cfe189782300dd28e0e))

### [1.0.1](https://github.com/Sekai-World/sekai-viewer/compare/v1.0.0...v1.0.1) (2021-12-08)


### Bug Fixes

* :bug: check currEvent before applying ([c28dc30](https://github.com/Sekai-World/sekai-viewer/commits/c28dc300dd3541064ce783e8f324b4214dc054a2))
* **user:** :bug: sekai deck back compatibility ([530a897](https://github.com/Sekai-World/sekai-viewer/commits/530a897433769a24da5c0aa4a5668dad5517f8ae))


### Refactors

* :lipstick: add loading animation to some images ([add1d2c](https://github.com/Sekai-World/sekai-viewer/commits/add1d2c117b3a458dae7c2edb310a2345b1204d2))

## [1.0.0](https://github.com/Sekai-World/sekai-viewer/compare/v0.9.6...v1.0.0) (2021-12-07)


### Features

* :sparkles: add asset viewer ([ca982c5](https://github.com/Sekai-World/sekai-viewer/commits/ca982c50a5a5b1dbb1e76ae6558b2899cd914d53))
* :sparkles: transition to mobx ([7c78db7](https://github.com/Sekai-World/sekai-viewer/commits/7c78db7d369e3893ff5b8fc13fc3ec67a5602dbd))
* **tools:** :sparkles: asset viewer with virtual scrolling ([b1b6800](https://github.com/Sekai-World/sekai-viewer/commits/b1b68009bb9e8bf001b16a9b8c8d00f51a358b38))


### Bug Fixes

* :rotating_light: resourceBox no unique key warning ([f63faf8](https://github.com/Sekai-World/sekai-viewer/commits/f63faf842b55a6b2b3faa500fdbecbc8a2c6815e))
* **card:** :bug: wrong birthday card maximum level ([ccba4fc](https://github.com/Sekai-World/sekai-viewer/commits/ccba4fc904ca32f68b05eea6effdf85f40455e01)), closes [#351](https://github.com/Sekai-World/sekai-viewer/issues/351)
* **user:** :bug: user login and logout redirection ([dd4993d](https://github.com/Sekai-World/sekai-viewer/commits/dd4993df9c23f580ab6369a05fd49c1d9a6200a2))
* **user:** :lipstick: sekai profile page layout ([7290d77](https://github.com/Sekai-World/sekai-viewer/commits/7290d778dc9a8373babee6096f555facffe7b556))

### [0.9.6](https://github.com/Sekai-World/sekai-viewer/compare/v0.9.5...v0.9.6) (2021-11-24)


### Bug Fixes

* :bug: language-cache empty problem causing user home blank ([97b5334](https://github.com/Sekai-World/sekai-viewer/commits/97b5334ba602d32be8e6a927c7896e0f9560b5f1))
* typo ([16ed29e](https://github.com/Sekai-World/sekai-viewer/commits/16ed29e8a82f7b1537363eec9b8bf33f31e70626))


### Refactors

* **user:** :recycle: let connect login fecth more data ([99ee5fc](https://github.com/Sekai-World/sekai-viewer/commits/99ee5fc2c300b3c4980cde62ac0d5168d05e4659))

### [0.9.5](https://github.com/Sekai-World/sekai-viewer/compare/v0.9.4...v0.9.5) (2021-11-16)


### Bug Fixes

* **user:** :bug: sekai components style and bug ([6ca723f](https://github.com/Sekai-World/sekai-viewer/commits/6ca723fb8e2de1198783732cfe51be4da29e529b))

### [0.9.4](https://github.com/Sekai-World/sekai-viewer/compare/v0.9.3...v0.9.4) (2021-11-16)


### Features

* **backend:** :sparkles: add refresh token, split sekai card and team from sekai profile ([61ec368](https://github.com/Sekai-World/sekai-viewer/commits/61ec368204587595052b3d7295f5ab85f29aa4ab))


### Bug Fixes

* **user:** :bug: login undefined user profile ([7814f41](https://github.com/Sekai-World/sekai-viewer/commits/7814f41324e80894752718d5c5f9116da83389f1))


### Refactors

* **backend:** :recycle: make changes according to endpoint split ([e0f6d0a](https://github.com/Sekai-World/sekai-viewer/commits/e0f6d0ad1d52bb12917d1afe8d5eba19af9eede6))
* **user:** :lipstick: sekai components code cleanup ([4def1c4](https://github.com/Sekai-World/sekai-viewer/commits/4def1c4dc9f28cbce2fbceecdb84c5a7fb6d84be))

### [0.9.3](https://github.com/Sekai-World/sekai-viewer/compare/v0.9.2...v0.9.3) (2021-11-12)


### Features

* **card:** :sparkles: add unit filter ([69b43c4](https://github.com/Sekai-World/sekai-viewer/commits/69b43c494b5dcb3e831c0f7cb9ed3a168212407d))
* **music:** :sparkles: meta table loading state ([886d985](https://github.com/Sekai-World/sekai-viewer/commits/886d9858518d32a773b846ff92aac6555bfe44a7))


### Bug Fixes

* :bug: filter state fix and cleanup ([77e452a](https://github.com/Sekai-World/sekai-viewer/commits/77e452ac70e837e4afcea6d5bc802764cc012ae2))
* :bug: horizontal scrollbar height ([487502c](https://github.com/Sekai-World/sekai-viewer/commits/487502ce256b5147ba8c0620f4e7a977ac8b26ee))
* **home:** :bug: table sorting uses new sortModel parameter ([321b68d](https://github.com/Sekai-World/sekai-viewer/commits/321b68d31253fe702baf206c4468fc7f7434c1fa))
* **tools:** :bug: music recommender crash for multi-live ([6f0e0e8](https://github.com/Sekai-World/sekai-viewer/commits/6f0e0e89f93c3486b29648634c7bc5125fc7d3ba))


### Refactors

* **card:** :lipstick: make comfy view more dense ([7c9ecc7](https://github.com/Sekai-World/sekai-viewer/commits/7c9ecc791c90c693c1dde29f570fe945adeac6ab))
* **home:** :recycle: remove table and dialog conditional rendering ([7e4b63b](https://github.com/Sekai-World/sekai-viewer/commits/7e4b63bc44f0c96b14e7ff251a6a5e00f4b69794))
* **music:** :lipstick: add icons to music tag ([db11315](https://github.com/Sekai-World/sekai-viewer/commits/db11315d7200711d25e92e9bdb13fbf680258f47))
* **tools:** :lipstick: event point calc autocomplete style fix ([d47a74a](https://github.com/Sekai-World/sekai-viewer/commits/d47a74acd373fc64eb60e98c2a682b10608205a7))

### [0.9.2](https://github.com/Sekai-World/sekai-viewer/compare/v0.9.1...v0.9.2) (2021-11-05)


### Refactors

* :recycle: remove redundant codes ([19e1034](https://github.com/Sekai-World/sekai-viewer/commits/19e103470cfbbd4c2472b893407052d080201d2c))

### [0.9.1](https://github.com/Sekai-World/sekai-viewer/compare/v0.9.0...v0.9.1) (2021-11-04)

## [0.9.0](https://github.com/Sekai-World/sekai-viewer/compare/v0.8.1...v0.9.0) (2021-11-04)


### Features

* **home:** :sparkles: make drawer swipeable on mobile device ([5dd5179](https://github.com/Sekai-World/sekai-viewer/commits/5dd51798f0868568fd8fe93c9d9a5b536107fc37))
* **home:** :sparkles: show game version info ([6807256](https://github.com/Sekai-World/sekai-viewer/commits/68072566635e3f9dd99a2513316a2193bf9af403))
* **layout:** :sparkles: store drawer open state on desktop ([9f4ffcb](https://github.com/Sekai-World/sekai-viewer/commits/9f4ffcb162102fdfd8fc45d62bfabf112ef2766b))
* **settings:** :sparkles: show detected client region ([679a1f4](https://github.com/Sekai-World/sekai-viewer/commits/679a1f4bdeecb392e350d52fad4d3122a1cc7a2e))
* **user:** :sparkles: show more sekai profile data ([b0c7694](https://github.com/Sekai-World/sekai-viewer/commits/b0c7694785db49509e2be4efb9b6afe3a1d49c8b))


### Bug Fixes

* :adhesive_bandage: rename AdSense to avoid wrong adblock rules ([b1ec37e](https://github.com/Sekai-World/sekai-viewer/commits/b1ec37e68280eae9690c7e6a94572e550a45f776))
* :rotating_light: missing `key` prop warning in AgendaView ([eff5d0c](https://github.com/Sekai-World/sekai-viewer/commits/eff5d0c9bebd67f3abf75b71316ec1e0a023192a))
* **music:** no `null` label for FormControlLabel ([ea62f1e](https://github.com/Sekai-World/sekai-viewer/commits/ea62f1e76c706540f04c033e20064a6478c69be0))
* **pwa:** :bug: use `manifest.webmanifest` in `index.html` ([1385ba1](https://github.com/Sekai-World/sekai-viewer/commits/1385ba11cdbc5a259baa7010ff91a2f99eda555e))


### Refactors

* :arrow_up: upgrade material-ui@4 to mui@5 alongwith dependencies ([c1dd350](https://github.com/Sekai-World/sekai-viewer/commits/c1dd350cf19e33313cee29bbcb52c8e040f90c1f))
* :building_construction: change folder structure ([a896a32](https://github.com/Sekai-World/sekai-viewer/commits/a896a326f9748081fc769dd2ba550a8a0ea43436))
* :hammer: migration to pnpm, vite ([5e66bd8](https://github.com/Sekai-World/sekai-viewer/commits/5e66bd83c2183a04edbf2956888a06f0e5d3edb7))
* :lipstick: dialog style fix ([5f3e0bd](https://github.com/Sekai-World/sekai-viewer/commits/5f3e0bd4070cc0f4f5382df6ed3c8a1545b36977))
* :recycle: remove useToggle for mobile drawer ([ea08f10](https://github.com/Sekai-World/sekai-viewer/commits/ea08f10fd3947eda59bc514fcbeab7cfdf57a12e))
* :recycle: save country as "unknown" instead of `undefined` ([1c7d56e](https://github.com/Sekai-World/sekai-viewer/commits/1c7d56ea91c771ae1983fb28a37259c28181eab6))
* **home:** :lipstick: shortcut section spacing adjustment ([0962140](https://github.com/Sekai-World/sekai-viewer/commits/09621409b26c5f08d02aec7865307b57840aa241))
* **pwa:** :recycle: use vite pwa plugin ([8827de0](https://github.com/Sekai-World/sekai-viewer/commits/8827de0b52f4ba34db8678312632458d820002fb))
* **user:** :lipstick: dialog with crousel style fix ([027ea11](https://github.com/Sekai-World/sekai-viewer/commits/027ea11e4ffd92a27894bef2ad8f0a18633e2842))

### [0.8.1](https://github.com/Sekai-World/sekai-viewer/compare/v0.8.0...v0.8.1) (2021-10-18)


### Bug Fixes

* **card:** birthday card rarity on detail page ([e5ccc4b](https://github.com/Sekai-World/sekai-viewer/commits/e5ccc4b10f53d98c1b52139c6a75912a7fe3d463))
* **comment:** list key warning ([582bd1f](https://github.com/Sekai-World/sekai-viewer/commits/582bd1f3320722c2bd51fd2fe0186c6a45435fe6))
* **event-tracker:** fetch correct regional graph ([c9cff47](https://github.com/Sekai-World/sekai-viewer/commits/c9cff47bdf937d74fce92af01c53851a0f536c7b))
* **event:** cards specific boost check condition ([b314b1f](https://github.com/Sekai-World/sekai-viewer/commits/b314b1f5798b06f6a36b9271cc2f7ca4fe773826))
* **settings:** warning ([05b4b9a](https://github.com/Sekai-World/sekai-viewer/commits/05b4b9a6ff734ea5e1ad3ce266465b850907a1c8))
* **subs:** avoid degree image find error ([4301179](https://github.com/Sekai-World/sekai-viewer/commits/43011796ae0fe9e282baea8d88e5cd7b08c8f0eb))
* **utils:** distinguish data cache key for fetched data ([3388f5e](https://github.com/Sekai-World/sekai-viewer/commits/3388f5e7f1a91204b9bffdc87a56b65f0723d7e3))

## [0.8.0](https://github.com/Sekai-World/sekai-viewer/compare/v0.7.2...v0.8.0) (2021-10-18)


### Features

* add separate settings page ([e0b7f72](https://github.com/Sekai-World/sekai-viewer/commits/e0b7f727ed6c8cc9411e6dd74b26dcec26f4912c))
* **event-tracker:** support multiple server region ([59d45c9](https://github.com/Sekai-World/sekai-viewer/commits/59d45c946b1d2e938e6d9d40657e3b7a23fd9d31))
* support multiple server region ([64c307d](https://github.com/Sekai-World/sekai-viewer/commits/64c307dcc6e6e52707c23816cda4c48bbe51d49d))
* **utils:** support multiple server regions ([38ceec3](https://github.com/Sekai-World/sekai-viewer/commits/38ceec3cd121f8cf2dee6fdd29d6c003b10bf9ca))


### Refactors

* **support:** remove container ([86cf630](https://github.com/Sekai-World/sekai-viewer/commits/86cf6303d2f4b6eece09b4b443495e5bee8f9783))

### [0.7.2](https://github.com/Sekai-World/sekai-viewer/compare/v0.7.1...v0.7.2) (2021-10-04)


### Bug Fixes

* **card:** card birthday frame ([9064146](https://github.com/Sekai-World/sekai-viewer/commits/9064146aefae5a342fba8138b5efc2a9d45e81c6))
* **card:** card detail birthday card thumb ([b581e6a](https://github.com/Sekai-World/sekai-viewer/commits/b581e6a8eeb548a5ce902c1ef63ab42a9e1d5637))
* **subs:** birthday card, trainable state ([e88a2e9](https://github.com/Sekai-World/sekai-viewer/commits/e88a2e981831042077f3801c3956e6e53b01f74a))
* **subs:** correctly handle thumb training status ([f3bbcf6](https://github.com/Sekai-World/sekai-viewer/commits/f3bbcf648c51d231a1ba27dec1633b894ddf45bb))
* **subs:** loadTeamDialog show card training status ([cbd69d8](https://github.com/Sekai-World/sekai-viewer/commits/cbd69d8c5227249faa7b8dfac5946f7181dfe289))

### [0.7.1](https://github.com/Sekai-World/sekai-viewer/compare/v0.7.0...v0.7.1) (2021-10-04)


### Features

* **card:** support birthday card ([f190891](https://github.com/Sekai-World/sekai-viewer/commits/f190891e40beceaa5cdf758df37e0141633f2af2))


### Bug Fixes

* **home:** haruka birthday banner date check ([e10db33](https://github.com/Sekai-World/sekai-viewer/commits/e10db33fe44dae6bf09f09a541d709a72c96b170))

## [0.7.0](https://github.com/Sekai-World/sekai-viewer/compare/v0.6.0...v0.7.0) (2021-10-03)


### Features

* **calc:** support event card related bonus ([18270b3](https://github.com/Sekai-World/sekai-viewer/commits/18270b35f5dfe765a5be3241ce0c19ec11a88895))
* **event-tracker:** add cheerful carnival team info ([85d1f11](https://github.com/Sekai-World/sekai-viewer/commits/85d1f11af7013379a8201d5c08d94293677770fb))
* **event:** add bonus rate for special cards ([7e05961](https://github.com/Sekai-World/sekai-viewer/commits/7e05961a25e9a38ade1c21a211feff85bf5b405a))
* **home:** add birthday banner of haruka and anniversary banner ([e46454f](https://github.com/Sekai-World/sekai-viewer/commits/e46454f88c7359b470cd2d6ebc610ab41fbdd593))
* **subs:** add cards diaglog improve ([65f2e37](https://github.com/Sekai-World/sekai-viewer/commits/65f2e374c3bfa355cf65a796722b55662c9fa2ff))


### Bug Fixes

* **gacha:** now able to sample the last element in card-list of each rarity ([f01ad9f](https://github.com/Sekai-World/sekai-viewer/commits/f01ad9f3936d5c410e46de878565b46c9791e19e))
* **subs:** degree image rank indicator not cleared ([e8758f0](https://github.com/Sekai-World/sekai-viewer/commits/e8758f0dd0a0cb55463dd64a1cd954f93b0d8983))


### Refactors

* make every externel url changable ([5cea1dd](https://github.com/Sekai-World/sekai-viewer/commits/5cea1dd9d915c7eac93abceade74e48083398929))
* **subs:** better clear degree rank indicator ([39179fe](https://github.com/Sekai-World/sekai-viewer/commits/39179fe15ba3eb0d27fb240f37c8158587bfe82e))

## [0.6.0](https://github.com/Sekai-World/sekai-viewer/compare/v0.5.9...v0.6.0) (2021-08-02)


### Features

* **calc:** give worst and best score for songs in song recommender ([45b312e](https://github.com/Sekai-World/sekai-viewer/commits/45b312eda7e7888bed208550f18c81f72c934d71))
* **music:** filter only valid (released) music meta ([da58fd7](https://github.com/Sekai-World/sekai-viewer/commits/da58fd72ad8874b1074f9aa79ffe67205bb78d28))
* **utils:** team builder allows filtering by skills ([4e514f9](https://github.com/Sekai-World/sekai-viewer/commits/4e514f905058c83924f7935bd218ab31feaffebe))


### Bug Fixes

* **calc:** wrong average skill rate for event point calc ([4b37840](https://github.com/Sekai-World/sekai-viewer/commits/4b378406ef803c68de4714283ddd71bfa63b810e))
* **user:** allow 18 digit sekai id ([c49dd7d](https://github.com/Sekai-World/sekai-viewer/commits/c49dd7d92319e30369bfd9e632d1feac7c9c3392)), closes [#333](https://github.com/Sekai-World/sekai-viewer/issues/333)


### Refactors

* **ad:** remove most ads ([c2b76ac](https://github.com/Sekai-World/sekai-viewer/commits/c2b76ace89e91f0ef55a65628ed818ba74fb8046))
* **calc:** add challenge live mode for event point calc, use filtered music meta ([4428733](https://github.com/Sekai-World/sekai-viewer/commits/4428733a51544179696e0cd034e6c0994c172305))
* **calc:** update event point formular, add challenge live point ([fedb984](https://github.com/Sekai-World/sekai-viewer/commits/fedb9845e566b9bfd3aeba8c1046bbe7a0618d6f))
* **skill:** adpot new skill type score_up_condition_life ([32d2d39](https://github.com/Sekai-World/sekai-viewer/commits/32d2d39823bb1f9761c574c79867a9fcc52b1fba))

### [0.5.9](https://github.com/Sekai-World/sekai-viewer/compare/v0.5.8...v0.5.9) (2021-07-12)


### Features

* **home:** add banner for nene and an's birthday ([1d73088](https://github.com/Sekai-World/sekai-viewer/commits/1d73088c8c3234240a1ceb016d35e9dceb43bf13))
* **music:** simplify trim slience, add flac support ([fc3bc1b](https://github.com/Sekai-World/sekai-viewer/commits/fc3bc1b81d1bb76719c9dbec4965ab49e274b771))
* **music:** tooltip for downloading flac ([ccb1cec](https://github.com/Sekai-World/sekai-viewer/commits/ccb1cecd0da7ed038c111c84013c8e02ba0f4294))


### Refactors

* **music:** only trim mp3 file for now ([da676ec](https://github.com/Sekai-World/sekai-viewer/commits/da676ecd234fd5e8b9ceede107230e94da2cb56d))

### [0.5.8](https://github.com/Sekai-World/sekai-viewer/compare/v0.5.7...v0.5.8) (2021-07-09)


### Bug Fixes

* **music:** mv type filter becomes true "AND" filter ([224e5ed](https://github.com/Sekai-World/sekai-viewer/commits/224e5ed06098f3d51b019d4ba5b1c1a274bd9fd2))

### [0.5.7](https://github.com/Sekai-World/sekai-viewer/compare/v0.5.6...v0.5.7) (2021-06-27)


### Features

* add comments for card, event, music and vlive ([4107baa](https://github.com/Sekai-World/sekai-viewer/commits/4107baa72c55c9d7aa75ed4c9cdfd1b0b385d1d2))
* **utils:** add api for proseka data ([cfa8915](https://github.com/Sekai-World/sekai-viewer/commits/cfa89150bc565aa33db4c9f48aea7c8d8719d5f2))


### Bug Fixes

* **comment:** missing style file, fetch comments on load ([995163b](https://github.com/Sekai-World/sekai-viewer/commits/995163b76a7beaa4812df826a59db744a74c677e))
* **music:** music video path ([b4f283c](https://github.com/Sekai-World/sekai-viewer/commits/b4f283c477934788e7f3e3fd6ec669b471ed296d))


### Refactors

* **announcement:** adaption for comment component  change ([fcd76be](https://github.com/Sekai-World/sekai-viewer/commits/fcd76beb58297d28e32ed1c060b7412b10ad22ac))
* **calc:** add difficulties back to event point calc ([93be7b0](https://github.com/Sekai-World/sekai-viewer/commits/93be7b0c00e5859f05350dd3edf77edf4b142827))
* **calc:** code cleanup ([f43ea36](https://github.com/Sekai-World/sekai-viewer/commits/f43ea361b160edddb58e689dbfd8f145b68561c6))

### [0.5.6](https://github.com/Sekai-World/sekai-viewer/compare/v0.5.5...v0.5.6) (2021-06-21)


### Bug Fixes

* movie player, story reader blank screen ([9d4c98c](https://github.com/Sekai-World/sekai-viewer/commits/9d4c98c03dd50a427cd425119d0231a50867c8a0))

### [0.5.5](https://github.com/Sekai-World/sekai-viewer/compare/v0.5.4...v0.5.5) (2021-06-21)


### Bug Fixes

* **subs:** degree image set background ([0d3b796](https://github.com/Sekai-World/sekai-viewer/commits/0d3b796709fc824f02eac86435b2d5abd5e8f4ec))

### [0.5.4](https://github.com/Sekai-World/sekai-viewer/compare/v0.5.3...v0.5.4) (2021-06-16)


### Features

* **storyreader:** add music and voice download button ([2231eec](https://github.com/Sekai-World/sekai-viewer/commits/2231eec27b34d2a87c089f48fd7235e4b761cd2f))
* update type definition ([44a21a1](https://github.com/Sekai-World/sekai-viewer/commits/44a21a16bfbbd6d3fd9201f1f76b07f0d119e68d))
* **utils:** add cheerful carnival event point calc ([dbb0fc4](https://github.com/Sekai-World/sekai-viewer/commits/dbb0fc4640cd7d4877c8bfce5b913d797ac219b2))


### Bug Fixes

* **ad:** typo of noAdRoles ([02a0b04](https://github.com/Sekai-World/sekai-viewer/commits/02a0b042c7262c2292c775c21a2b4f308de487d3))
* support page patreon list ([36b6841](https://github.com/Sekai-World/sekai-viewer/commits/36b68411b3e5513bbb50d59011baa6d1a7e0460d))


### Refactors

* **event_calc:** great functionality enrichment ([08b4001](https://github.com/Sekai-World/sekai-viewer/commits/08b400133c2f4dfbb255c3109bc44d1fa4a136e2))
* **muisc_recomm:** remove event point calc ([abb217a](https://github.com/Sekai-World/sekai-viewer/commits/abb217a37c9fde951d047b5c6c2bbd72a0c779dc))
* **music:** audio player download link add download attribute ([eb96147](https://github.com/Sekai-World/sekai-viewer/commits/eb96147d6e0f2b118ce86945afd65f9952588444))
* **subs:** add cardStates param to calcTotalPower function ([8147f9a](https://github.com/Sekai-World/sekai-viewer/commits/8147f9a25ce30562ed78dbe980d79581490b5404))
* **user:** avoid loading too much assets once ([b313607](https://github.com/Sekai-World/sekai-viewer/commits/b3136074dc7bc1e372f46426cb51b90ce7e2f5bd))
* **user:** rename teamPowerStates to teamTotalPower ([e25243d](https://github.com/Sekai-World/sekai-viewer/commits/e25243d5c3250666b93f601139161b1c15a66fe8))

### [0.5.3](https://github.com/Sekai-World/sekai-viewer/compare/v0.5.2...v0.5.3) (2021-05-10)


### Features

* add story reader link to detail pages ([838e7ba](https://github.com/Sekai-World/sekai-viewer/commits/838e7ba03a98babfb8760c0074e8a25e19d4bbe4))


### Bug Fixes

* **event:** boost cards align with event cards on sm screen ([ab2c20f](https://github.com/Sekai-World/sekai-viewer/commits/ab2c20f3b7946500ef9cf5e3553af3b2e17903cf))
* **event:** detail page boost attribute align with boost characters ([2286ab4](https://github.com/Sekai-World/sekai-viewer/commits/2286ab4c2fe4a0d8dd53388f820a32497c147f79))
* **subs:** audio player volume reset after change source ([07e00fa](https://github.com/Sekai-World/sekai-viewer/commits/07e00fa3ad501fc7cbf856224fe0d746fceb8bf2))
* **user:** allow 17-digit sekai id ([e8a0acc](https://github.com/Sekai-World/sekai-viewer/commits/e8a0acc40348ef36847bff47d1ccad926fb58386))


### Refactors

* **storyreader:** disable transition of images ([02eae15](https://github.com/Sekai-World/sekai-viewer/commits/02eae152e17321f159a966f152b0dd29a8a55f7a))
* **subs:** material icon disable transition ([54ad9b7](https://github.com/Sekai-World/sekai-viewer/commits/54ad9b7ef6d3cdcd2d28ecfd955b4670995a63a5))

### [0.5.2](https://github.com/Sekai-World/sekai-viewer/compare/v0.5.1...v0.5.2) (2021-05-07)


### Features

* **event:** event tracker live row background change upon update ([d410ec1](https://github.com/Sekai-World/sekai-viewer/commits/d410ec1413f12538e096565a8f66d362d99b39c6))
* **storyreader:** support map talk ([9909cc2](https://github.com/Sekai-World/sekai-viewer/commits/9909cc2b69a613e6de9d9acddc24cc57abf55b45))


### Bug Fixes

* **context:** sekai profile local storage update with wrong content ([de0d891](https://github.com/Sekai-World/sekai-viewer/commits/de0d891eeab03b7cde5e096469b9bd7779649b64))
* **event:** sekai event record error message ([c5fcee8](https://github.com/Sekai-World/sekai-viewer/commits/c5fcee82e53b1e4fe59cc750f7ba54501e90a810))
* **music:** actual playback time varies ([e67bd40](https://github.com/Sekai-World/sekai-viewer/commits/e67bd40b1f6ab623c35bff77465e0320790893a9))
* **team:** medium thumb xs column 4 instead of 2 ([6b66371](https://github.com/Sekai-World/sekai-viewer/commits/6b66371291ee44a27896c908c8ffd76ccdcfc245))
* **tools:** score calc skill effect type crash ([bd4cb5d](https://github.com/Sekai-World/sekai-viewer/commits/bd4cb5db4510501b10d2800e8739ea68450e2ea3))
* **tools:** table row warning ([7496225](https://github.com/Sekai-World/sekai-viewer/commits/7496225a1c3db2324317c140dd4332d4edb6e537))
* **user:** check if sekai id is malformed before verification ([bdf965b](https://github.com/Sekai-World/sekai-viewer/commits/bdf965b246184d14d8f748406745ee804b94287d))
* **user:** new registered user login but blank screen ([c05b44b](https://github.com/Sekai-World/sekai-viewer/commits/c05b44b1225b475652293e18de09e7e0dce58419))


### Refactors

* **event:** event tracker update color use warning color ([ba8fee3](https://github.com/Sekai-World/sekai-viewer/commits/ba8fee35d297384bba81d1dd92da277a07c80ddb))
* **music:** agenda view type use chip ([a44c586](https://github.com/Sekai-World/sekai-viewer/commits/a44c5869fd23ac54e8660ac1b4b3d3699822919b))
* **storyreader:** change story reader entry layout ([76c3feb](https://github.com/Sekai-World/sekai-viewer/commits/76c3feb40262e742c8c51bf02475fe15b2cb43b7))
* **utils:** remove contentTransMode argument of getTranslated ([1ce1548](https://github.com/Sekai-World/sekai-viewer/commits/1ce1548f0296e29f15931baa1eff4131407762a3))
* **utils:** remove contentTransMode for useCharaName ([ae31c56](https://github.com/Sekai-World/sekai-viewer/commits/ae31c568e81afdff375682900e27322af5add250))

### [0.5.1](https://github.com/Sekai-World/sekai-viewer/compare/v0.5.0...v0.5.1) (2021-04-30)


### Features

* use global snackbar provider ([2117c9a](https://github.com/Sekai-World/sekai-viewer/commits/2117c9ab43af52898a39617ba1ba1126300784ae))


### Bug Fixes

* **context:** updateSekaiProfile set wrong localstorage content ([1a2d71c](https://github.com/Sekai-World/sekai-viewer/commits/1a2d71c8049b0838dcd88d0cb7a465505576ef56))
* **i18n:** namespace missing ([4aa1ed9](https://github.com/Sekai-World/sekai-viewer/commits/4aa1ed9eece1c521546b814984fd3dec35245142))
* **vlive:** agenda view image wrong place ([3ac9233](https://github.com/Sekai-World/sekai-viewer/commits/3ac9233c872eb30f62809612730b9e18a43a0e63))
* **vlive:** agenda view route endpoint ([d31176d](https://github.com/Sekai-World/sekai-viewer/commits/d31176d3870ed2b30fd98afe80139888c27ae7fa))


### Refactors

* **music:** if trim mp3 failed, try clean cache ([8ef453c](https://github.com/Sekai-World/sekai-viewer/commits/8ef453c259698cbb3453947ae345495e532e225f))
* **user:** sekai profile user statistics use accordion ([26f2e45](https://github.com/Sekai-World/sekai-viewer/commits/26f2e45c3efaaba5327eb41d6d706900b50cf3e4))
* **user:** user area items shown by areas ([05a01a0](https://github.com/Sekai-World/sekai-viewer/commits/05a01a00a21995051468e221c5570009775bdcb6))

## [0.5.0](https://github.com/Sekai-World/sekai-viewer/compare/v0.4.15...v0.5.0) (2021-04-29)


### Features

* **event:** cheerful carnival information ([fd010a7](https://github.com/Sekai-World/sekai-viewer/commits/fd010a706998aea45031afcf1d520100b357035e))
* **music:** music list filter enrichment ([0292b37](https://github.com/Sekai-World/sekai-viewer/commits/0292b37e578214d3a8b1c1da051f38e99eef3e23))
* **setting:** make spoiler switch opt-in ([032439c](https://github.com/Sekai-World/sekai-viewer/commits/032439c29eef31d4af6f0546c72a7b6c382b9135))
* **user:** user page sectioning ([81cf0e5](https://github.com/Sekai-World/sekai-viewer/commits/81cf0e5dc0ece4af1028f8d70005a4e6d9a6bd6c))


### Bug Fixes

* charaNameTrans component text color ([916db4e](https://github.com/Sekai-World/sekai-viewer/commits/916db4e4234979c214eda20a23637dbb0cf0810c))
* **music:** wrong number of dancer memebers ([62bcc21](https://github.com/Sekai-World/sekai-viewer/commits/62bcc21475ffdd1daf1d35eacf8825569d5afdb2))


### Refactors

* **vlive:** use image in list instead of CardMedia ([9993c3c](https://github.com/Sekai-World/sekai-viewer/commits/9993c3cf4f04eb68c6f2c742258bec8d249d429d))
* enlarge container to md ([33398d1](https://github.com/Sekai-World/sekai-viewer/commits/33398d1db44945e43d3195003822c5b9976a3913))
* **music:** make agenda view more compat ([dc94b42](https://github.com/Sekai-World/sekai-viewer/commits/dc94b42acd549f05152f4e33286eb3a69da384bb))
* **widget:** current event widget banner enlarge on mobile ([c22ba6d](https://github.com/Sekai-World/sekai-viewer/commits/c22ba6dc6f302ef83886074ca88550df6603f2fb))

### [0.4.15](https://github.com/Sekai-World/sekai-viewer/compare/v0.4.14...v0.4.15) (2021-04-21)


### Features

* **style:** add pointer interactive style ([857eef9](https://github.com/Sekai-World/sekai-viewer/commits/857eef907ed84804c5316eddb880539c204e9ce4))


### Bug Fixes

* **event:** event tracker crash when specific rank is not available ([8542f99](https://github.com/Sekai-World/sekai-viewer/commits/8542f99dda986e9c5ad1055ed6328c96bbc9ad94))
* **event:** show boost cards only before event starts ([6a55f84](https://github.com/Sekai-World/sekai-viewer/commits/6a55f846156a8a54cfc888e9ebb94725d16c4971))
* **stamp:** typo ([bf89975](https://github.com/Sekai-World/sekai-viewer/commits/bf89975738c8e5468ecf9653a2a3a431cd2070a2))
* **user:** added sekai card are not filtered out properly ([d82f418](https://github.com/Sekai-World/sekai-viewer/commits/d82f418859bd5f70d8c011554c589360be77f4c3))
* **virtual_live:** birthday live honor reward ([58426cf](https://github.com/Sekai-World/sekai-viewer/commits/58426cfad0eb92e6d40f9d6670653f6b8c171b2a))


### Refactors

* **event:** event image show using image component ([d2d3f11](https://github.com/Sekai-World/sekai-viewer/commits/d2d3f11de76c0daa6361d0a8df009c5c6410b724))
* **home:** move links to shortcuts ([ebff4ae](https://github.com/Sekai-World/sekai-viewer/commits/ebff4ae4ec0eaff2dc2670b33a12e39e86114956))

### [0.4.14](https://github.com/Sekai-World/sekai-viewer/compare/v0.4.13...v0.4.14) (2021-04-05)


### Features

* **comic:** add en translation ([3bdd2c0](https://github.com/Sekai-World/sekai-viewer/commits/3bdd2c02b67de3f95d1ce61651c0bf2619853f5c))
* **stamp:** add filter for text ([1675e5b](https://github.com/Sekai-World/sekai-viewer/commits/1675e5b7162943bb8737109c1aa91e74afd17f11))
* **support:** patron list from strapi ([c099ac3](https://github.com/Sekai-World/sekai-viewer/commits/c099ac3281689c90e59229f9fe73aa49dacfba87))

### [0.4.13](https://github.com/Sekai-World/sekai-viewer/compare/v0.4.12...v0.4.13) (2021-03-31)


### Bug Fixes

* **event:** eventTracker blank page ([c39cea9](https://github.com/Sekai-World/sekai-viewer/commits/c39cea95312818187d4198ecfeaec76a04d82914))
* useLocalStorage allow false value to be set ([a09b9fe](https://github.com/Sekai-World/sekai-viewer/commits/a09b9fe8ffe32bbb4225f9b7e07a79664c073d63))

### [0.4.12](https://github.com/Sekai-World/sekai-viewer/compare/v0.4.10...v0.4.12) (2021-03-30)


### Features

* **music:** add link to chart image ([891076f](https://github.com/Sekai-World/sekai-viewer/commits/891076fdb53835dff3365a1b86022574668e4624))


### Bug Fixes

* **music:** trim music following vocal type ([da1b09c](https://github.com/Sekai-World/sekai-viewer/commits/da1b09c4983f27fdc21c4b566df65dd1fba8c98b))
* avoid ToggleButtonGroup becomes null value ([3a773eb](https://github.com/Sekai-World/sekai-viewer/commits/3a773ebfa767bf21e8586d2d1c566f8ff4f18448))


### Refactors

* **card:** card detail page layout optimize ([01c8f68](https://github.com/Sekai-World/sekai-viewer/commits/01c8f682fc3e3ed27fbbe3e57964af04ecf264b6))
* **music:** make mp3 trim only when toggle is turned on ([47b325d](https://github.com/Sekai-World/sekai-viewer/commits/47b325dfdddacf549a08f3ad437e84766c7f06f2))

### [0.4.11](https://github.com/Sekai-World/sekai-viewer/compare/v0.4.10...v0.4.11) (2021-03-29)


### Features

* **music:** add link to chart image ([7c2c02b](https://github.com/Sekai-World/sekai-viewer/commits/7c2c02b0d0ac94992496fad3aa03734cb223b422))


### Bug Fixes

* avoid ToggleButtonGroup becomes null value ([46b75c8](https://github.com/Sekai-World/sekai-viewer/commits/46b75c8f6ad2414dc243b10622f4cf27315c5226))


### Refactors

* **card:** card detail page layout optimize ([23f637f](https://github.com/Sekai-World/sekai-viewer/commits/23f637f0ffa00b2d098fd8ab673d41e7bd798795))
* **music:** make mp3 trim only when toggle is turned on ([17a8715](https://github.com/Sekai-World/sekai-viewer/commits/17a87158feeda1daa9a6bb77e45f4f0d7893b86f))

### [0.4.10](https://github.com/Sekai-World/sekai-viewer/compare/v0.4.9...v0.4.10) (2021-03-19)


### Features

* **event:** add boost cards and virtual live section ([b30806f](https://github.com/Sekai-World/sekai-viewer/commits/b30806fb62d7289fb85a9b49d6c1e335d2a85a3c))
* user can control whether to display spoiler content ([3f22a94](https://github.com/Sekai-World/sekai-viewer/commits/3f22a940d2c463d16d49fe3ea0b17544f2256175))
* **card:** add gacha phrase with audio ([ad10d34](https://github.com/Sekai-World/sekai-viewer/commits/ad10d34af27774815c2f0a5c6292031d451b55d7))


### Bug Fixes

* **event:** handle event without virtual live ([e74c95e](https://github.com/Sekai-World/sekai-viewer/commits/e74c95efb0ae767c136f6887cdd73aa3842c62fb))
* card list filter dispatch function name ([124bd21](https://github.com/Sekai-World/sekai-viewer/commits/124bd21d2f06ed42aee2afe372bc0e5aee3fdea1))
* **card:** card list repeat no key warning ([a14fa2c](https://github.com/Sekai-World/sekai-viewer/commits/a14fa2c4d1fbe0072ff1156320c9187dcfed1646))
* **misc:** audio play button unload howl on unmount ([5d0a328](https://github.com/Sekai-World/sekai-viewer/commits/5d0a3286c649d6d7dc4f71a75a54dc3d43167628))
* **utils:** useLocalStorage reset value upon error ([503bdd0](https://github.com/Sekai-World/sekai-viewer/commits/503bdd0c044fa6da857811792d27265e590cd7df))


### Refactors

* index check sekai profile update as well ([1856756](https://github.com/Sekai-World/sekai-viewer/commits/18567563842cd5eec716c564621b4f5f2687d398))

### [0.4.9](https://github.com/Sekai-World/sekai-viewer/compare/v0.4.8...v0.4.9) (2021-03-09)


### Features

* **music:** add music meta page ([f85555f](https://github.com/Sekai-World/sekai-viewer/commits/f85555fff9de56499c074a6669cedb2c37b0309a))
* **subs:** add padding to popover ([818d6f8](https://github.com/Sekai-World/sekai-viewer/commits/818d6f8a6c3cf2c553b15fcd478d7883cc6b1fb4))


### Refactors

* **mr:** table columns layout optimization ([bd16beb](https://github.com/Sekai-World/sekai-viewer/commits/bd16bebbb1527e9d993f34bccf1312e92549a829))
* **mr:** table refine ([1338bce](https://github.com/Sekai-World/sekai-viewer/commits/1338bce724087b58459ecafcabe44235b1f81e15))
* **utils:** update music meta url ([8fd6e2c](https://github.com/Sekai-World/sekai-viewer/commits/8fd6e2c9584e0ac014f2c97649708abebe2549af))

### [0.4.8](https://github.com/Sekai-World/sekai-viewer/compare/v0.4.7...v0.4.8) (2021-03-03)


### Features

* **card:** only show support unit filter when vs character selected ([bf1bc54](https://github.com/Sekai-World/sekai-viewer/commits/bf1bc5498ee93bbf178c51af105c2c19cbf87667))
* **event:** add sekai event record to event tracker ([dcdc811](https://github.com/Sekai-World/sekai-viewer/commits/dcdc811b6bc25e4dff03eef5eee770622bf4569d))
* **music:** jacket for sekai ver of charles ([50b4ad9](https://github.com/Sekai-World/sekai-viewer/commits/50b4ad979b97ff26b6567a10925ee927968e41b8))
* **user:** allow user check event record in the past ([1406dc8](https://github.com/Sekai-World/sekai-viewer/commits/1406dc89fa69a3e204debd7c40538c12e8950857))
* **user:** card filter sync to card list ([230c02e](https://github.com/Sekai-World/sekai-viewer/commits/230c02e8ec6d0919be135a64eade794c387caeb0))


### Bug Fixes

* **event:** disable time travel slider when fetching data ([5e4c5b5](https://github.com/Sekai-World/sekai-viewer/commits/5e4c5b5ff5c7765dc1770eaf49faef68e62d9597))
* **event:** event tracker current event button does not fetch data ([3995b78](https://github.com/Sekai-World/sekai-viewer/commits/3995b7880cc2f5129310884a68a67721cd5b0e37))
* **user:** music statistics full combo count ([9aff556](https://github.com/Sekai-World/sekai-viewer/commits/9aff5561328988e66e1900aad2f378f9892f9f5b))


### Refactors

* update service worker cache strategy ([a0d6cc6](https://github.com/Sekai-World/sekai-viewer/commits/a0d6cc6c01a89890580b1fc3922e7e036dca0f99))

### [0.4.7](https://github.com/Sekai-World/sekai-viewer/compare/v0.4.6...v0.4.7) (2021-02-20)


### Features

* add placeholder for event analyzer ([48f3221](https://github.com/Sekai-World/sekai-viewer/commits/48f3221d7f3fc3183a0f0e43f3b79086e1bb07f6))
* **event:** event tracker time travel ([ea49c1a](https://github.com/Sekai-World/sekai-viewer/commits/ea49c1a8875a9885bff162dd8b16f021ba0f2e72))


### Bug Fixes

* **event:** add missing prediction to event tracker mobile view ([05b4da1](https://github.com/Sekai-World/sekai-viewer/commits/05b4da1a0ffdcc45ee39372a08b23938f44185e5))
* **event:** add show full rank switch to event tracker ([bd55669](https://github.com/Sekai-World/sekai-viewer/commits/bd556696977b5919048353db26e12c562fe7b011))


### Refactors

* **event:** event tracker better mobile view, remove unnecessary buttons ([da19859](https://github.com/Sekai-World/sekai-viewer/commits/da19859defdae25ed7d071a30641893e06c93767))

### [0.4.6](https://github.com/Sekai-World/sekai-viewer/compare/v0.4.5...v0.4.6) (2021-02-18)


### Features

* **degree:** show degree level icons ([ba6a13f](https://github.com/Sekai-World/sekai-viewer/commits/ba6a13f924724fb15d777f5430b4eb645b859e46))
* **user:** sekai profile music statistics ([aaa77bc](https://github.com/Sekai-World/sekai-viewer/commits/aaa77bcca11846f60e267a5c80ab53404bf9147d))


### Bug Fixes

* **unit-detail:** music name use translation ([4b2b7b0](https://github.com/Sekai-World/sekai-viewer/commits/4b2b7b0034b3467903ad134f80fe94e0146dd8f4))
* **widget:** event banner no jump ([36d8c5e](https://github.com/Sekai-World/sekai-viewer/commits/36d8c5ead6ce6a3a0f510601404c674ca1f192be))


### Refactors

* **event:** event tracker layout refine ([2b8de3c](https://github.com/Sekai-World/sekai-viewer/commits/2b8de3c8aadb57f45cfb8faec99c4ef25e4b019f))
* change adsense behaviour ([3d95319](https://github.com/Sekai-World/sekai-viewer/commits/3d95319bad44fb1279714840fc977340772f91fd))
* unregister service worker if hostname not match ([6f3ace6](https://github.com/Sekai-World/sekai-viewer/commits/6f3ace6cfe00ea3a0a17a945759b69a6f6c713b0))

### [0.4.5](https://github.com/Sekai-World/sekai-viewer/compare/v0.4.4...v0.4.5) (2021-02-12)


### Features

* **filter:** stamp list character filter local storage ([2d93902](https://github.com/Sekai-World/sekai-viewer/commits/2d93902f968f9c55087dc4055b46a93ce9e9f102))
* card filter of event bonuses ([73d3c73](https://github.com/Sekai-World/sekai-viewer/commits/73d3c73bc7170e1c52c63c5cdf908ab4d748aee7))
* **user:** better card importer ([ccc6829](https://github.com/Sekai-World/sekai-viewer/commits/ccc6829a97d0371d7cf53422e54fa2aa55c39aa9))


### Bug Fixes

* **music:** music tag translation empty ([463f1dd](https://github.com/Sekai-World/sekai-viewer/commits/463f1dd6b2490f8dde77ebb1df22a99bebea3be8))

### [0.4.4](https://github.com/Sekai-World/sekai-viewer/compare/v0.4.3...v0.4.4) (2021-02-11)


### Bug Fixes

* **live2d:** small screen size error, avoid loading interruption ([a271938](https://github.com/Sekai-World/sekai-viewer/commits/a27193893ad90ee325cb16cf96becb3f737b6e02))


### Refactors

* **card:** agenda view fit large screen ([8e3723c](https://github.com/Sekai-World/sekai-viewer/commits/8e3723c5d824cfc467da9053237a68b558c32b1e))
* use useLocalStorage hooks instead of setItem ([633d8fe](https://github.com/Sekai-World/sekai-viewer/commits/633d8fe02372f521cecb4b06c11a3d691ad03de0))

### [0.4.3](https://github.com/Sekai-World/sekai-viewer/compare/v0.4.2...v0.4.3) (2021-02-08)


### Features

* **card:** filter local storage save, add reset filter button ([89b566b](https://github.com/Sekai-World/sekai-viewer/commits/89b566bc08e20e10019b40176c53036119a3645a))
* **honor:** list filter memory in local storage ([f9860ae](https://github.com/Sekai-World/sekai-viewer/commits/f9860ae222e801f8707e53433ce6eb89e845f1ea))
* **misson:** list filter memory using local storage ([cd47dbe](https://github.com/Sekai-World/sekai-viewer/commits/cd47dbe864cd49495ae320d204c9d4432c6052a2))
* **music:** do same thing as in card list filter ([1bc0ca7](https://github.com/Sekai-World/sekai-viewer/commits/1bc0ca71687fbb1e539889c102c5d78ea781b3bb))
* skill filter for cardList ([bfe4e3c](https://github.com/Sekai-World/sekai-viewer/commits/bfe4e3c7b7de359dd4bd0cc374d02172cf136d01))


### Bug Fixes

* **card:** remove warning ([19f298e](https://github.com/Sekai-World/sekai-viewer/commits/19f298ed29b82bca276e392fa6dee012ae4683ac))
* **stamp:** download url ([111cb71](https://github.com/Sekai-World/sekai-viewer/commits/111cb71b5050235eaa9f0205984654c164be5adc))
* **team:** fix build ([ed20745](https://github.com/Sekai-World/sekai-viewer/commits/ed2074559089c3e58d34b7ff540a522a1814dc4e))
* **team:** team power calculation ([f5ee163](https://github.com/Sekai-World/sekai-viewer/commits/f5ee1633fe1ac1df8428142e9f8cb5cd6c270b18))
* **user:** "perfect_score_up" skill type filtering ([8f6b56b](https://github.com/Sekai-World/sekai-viewer/commits/8f6b56bd891a7f8f08c7e5a6725878f755545ce5))
* **user:** cannot add card when card list is empty ([e9c7321](https://github.com/Sekai-World/sekai-viewer/commits/e9c7321b6c040338bf10569066bb55753be48cd4))


### Refactors

* filter dense layout ([801a447](https://github.com/Sekai-World/sekai-viewer/commits/801a4475bd1a06789c3cae4cf9787af9b97d8814))

### [0.4.2](https://github.com/Sekai-World/sekai-viewer/compare/v0.4.1...v0.4.2) (2021-02-04)


### Features

* **user:** add user sekai statistics panel ([c91eedc](https://github.com/Sekai-World/sekai-viewer/commits/c91eedc4575dedd56ff96b77dd6cca5189410c03))
* add area items cached data ([56bc7a8](https://github.com/Sekai-World/sekai-viewer/commits/56bc7a8eb3d40657268444919468488235713625))
* **user:** show user honors in sekai profile ([3198142](https://github.com/Sekai-World/sekai-viewer/commits/31981425a42459ef3f4df0faef8f07483cdfd6f3))


### Bug Fixes

* **about:** it translator name ([27f5b0e](https://github.com/Sekai-World/sekai-viewer/commits/27f5b0e4d21adea53193933a01be9b3a5f7de1e3))
* **user:** missing close button of help carousel ([70f11e4](https://github.com/Sekai-World/sekai-viewer/commits/70f11e4137bd5c5f47438c71b059ad110defce74))


### Refactors

* improve adsense block display ([3fe781c](https://github.com/Sekai-World/sekai-viewer/commits/3fe781c5a0379110c71a9fa780813a752a155784))

### [0.4.1](https://github.com/Sekai-World/sekai-viewer/compare/v0.4.0...v0.4.1) (2021-02-03)


### Features

* **user:** add help to import cards ([9d44612](https://github.com/Sekai-World/sekai-viewer/commits/9d446126fb5b826d80cb89a6e1e07998e4eb58a3))
* add adsense blocks ([9c666f2](https://github.com/Sekai-World/sekai-viewer/commits/9c666f26a7463b8073440f904a607253dd2604d0))


### Bug Fixes

* **team-build:** add card crash if not logged in ([31d7441](https://github.com/Sekai-World/sekai-viewer/commits/31d7441d411f69af0a0c343b0e11221ba8bbd6df))
* **user:** import tweak to solve some screenshot matching problem ([f8077b1](https://github.com/Sekai-World/sekai-viewer/commits/f8077b1579b9a84115c74fffe65278b04c6efff6))


### Refactors

* **user:** reduce tesseract worker count to 1 to save memory ([c6d9b06](https://github.com/Sekai-World/sekai-viewer/commits/c6d9b069e032ad52061be096ecefb232212d09da))

## [0.4.0](https://github.com/Sekai-World/sekai-viewer/compare/v0.3.2...v0.4.0) (2021-01-30)


### Features

* **api:** add putSekaiDeckList and deleteSekaiDeckList ([ad5ce76](https://github.com/Sekai-World/sekai-viewer/commits/ad5ce762f736c1055d056627c6fc634a1d64cf8a))
* **card:** medium thumbnail supports showing card power as well ([95511cd](https://github.com/Sekai-World/sekai-viewer/commits/95511cde0cb631565d015325e21248db3b9b6458))
* **card:** thumbnail show card data ([5cf7779](https://github.com/Sekai-World/sekai-viewer/commits/5cf77793e340d30f08dbeb9061d707ee3ded3d7d))
* **user:** add sekai card management board ([0b1e50c](https://github.com/Sekai-World/sekai-viewer/commits/0b1e50c74b5f0d59171b2bc2e42e690059c8d43b))
* **user:** allow modify skill level upon importing and modifying in list ([7931948](https://github.com/Sekai-World/sekai-viewer/commits/79319480f28c691fb778b620957f44c115ddc9c8))
* **user:** allow partial update sekai profile and user meta ([4c73e08](https://github.com/Sekai-World/sekai-viewer/commits/4c73e08f80e39ba0ec2421e02c27bf3c105637a1))
* **user:** import sekai cards ([76586e7](https://github.com/Sekai-World/sekai-viewer/commits/76586e7c505df215909763c7fe541e575e3be84d))
* **user:** load sekai user team ([6386169](https://github.com/Sekai-World/sekai-viewer/commits/6386169d819e0e580f6e7d7177bbb28cfb8c8f95))
* **user:** sekai profile sub components lazy laoding ([ad7d665](https://github.com/Sekai-World/sekai-viewer/commits/ad7d6650b2d1a75c88ec733ebb73bbca1cb96e1a))
* **utils:** add useLocalStorage and useToggle hooks ([0d8d7e9](https://github.com/Sekai-World/sekai-viewer/commits/0d8d7e95b81b88a2c1e0e18b62072529703e69ca))


### Bug Fixes

* **card:** thumbnail rarity star position ([eb4c394](https://github.com/Sekai-World/sekai-viewer/commits/eb4c394e2deac992a38f3a35bac93b07ea293356))
* **music:** audio player animation stop after seeking ([9029ec5](https://github.com/Sekai-World/sekai-viewer/commits/9029ec5bd8e52dd923091f9e64f05258d08aa9de))
* **music-recommend:** typo ([d800b76](https://github.com/Sekai-World/sekai-viewer/commits/d800b76bc1431220b7c479d0b82aaca787b184f6))
* **types:** remove SekaiCard, use ITeamCardState directly ([6fe9ad9](https://github.com/Sekai-World/sekai-viewer/commits/6fe9ad97dd1a078fa15d169349462dcb34dfbe27))
* **user:** correct auto total power calc process ([30a4e22](https://github.com/Sekai-World/sekai-viewer/commits/30a4e22355a49fd6391ccab3197dc84feda2c45b))
* **user:** due to change of other module ([0c4ab44](https://github.com/Sekai-World/sekai-viewer/commits/0c4ab446349a759b86f1c101b53ed690826667d3))
* **user:** sekai profile crash when no sekai profile created ([f674ec8](https://github.com/Sekai-World/sekai-viewer/commits/f674ec80b4ac0f501cfb6e112e144917225f1e18))
* card master rank icon level 5 ([4705fb8](https://github.com/Sekai-World/sekai-viewer/commits/4705fb8ddde251990379fd1d1fbdb226f8a1c444))
* preview download png instead of webp ([5a61fe1](https://github.com/Sekai-World/sekai-viewer/commits/5a61fe15c86fb0f40104f21617018e123c98d54d))


### Refactors

* **api:** strapi card model fix, add put and delete sekai card list api ([5c196c6](https://github.com/Sekai-World/sekai-viewer/commits/5c196c62cd54c108d99566c543dfee916963d1a5))
* **live2d:** read model list from remote ([1fbe666](https://github.com/Sekai-World/sekai-viewer/commits/1fbe666278a983a962eabc91455046605483395e))
* **user:** import card power instead of level ([83ed3b6](https://github.com/Sekai-World/sekai-viewer/commits/83ed3b653c43c242d9a6273d3d6a6e9618bbfd00))
* **user:** load team sekai team text change and space between sections ([18004d1](https://github.com/Sekai-World/sekai-viewer/commits/18004d10e2d18a8644452fa76f54f762d6b52fad))
* **user:** move update sekai profile button to same line of sekai id ([b130018](https://github.com/Sekai-World/sekai-viewer/commits/b130018de95a0d4a771443869b9e9cda39a4c360))
* **user:** remove unnecessary console.log ([793ce9e](https://github.com/Sekai-World/sekai-viewer/commits/793ce9e5a3195c454381af01071da7ca40320dfd))
* **user:** sekai id panel layout fix ([55308ae](https://github.com/Sekai-World/sekai-viewer/commits/55308aefefc7437cac614dde0a6fe1855c0b6b69))
* **user:** store more card states for calculating card power ([31fd647](https://github.com/Sekai-World/sekai-viewer/commits/31fd6472fbaf5b654c463067732eaaf5e08555f2))
* **user:** team manager layout change, edit card power, auto calc total power ([7288929](https://github.com/Sekai-World/sekai-viewer/commits/72889298949caab47599f6c82fff52d68e8d3a59))
* **user:** user card list changes when cloud card list changes ([9cdf769](https://github.com/Sekai-World/sekai-viewer/commits/9cdf7693e72eacef74e9ba3c8474f2b282aa252c))
* modify global scrollbar style (only for webkit) ([90badc9](https://github.com/Sekai-World/sekai-viewer/commits/90badc9aef7dcbaae7bf2000cbddccc11c1719b7))

### [0.3.2](https://github.com/Sekai-World/sekai-viewer/compare/v0.3.1...v0.3.2) (2021-01-18)


### Features

* sort by id for all list page ([a4f755e](https://github.com/Sekai-World/sekai-viewer/commits/a4f755e118b62bebd41e11e8e0393491d4f7ba2b))
* **event:** allow track more rankings ([d57d8fa](https://github.com/Sekai-World/sekai-viewer/commits/d57d8fae1eb887e1e015ce235d94b0999eeded6d))
* **music:** add music mv type filter ([2591712](https://github.com/Sekai-World/sekai-viewer/commits/25917120f277819d8e0a3891a7dd33191978760d))


### Bug Fixes

* language code not in list may cause error ([e7c9587](https://github.com/Sekai-World/sekai-viewer/commits/e7c9587052e07ef632bd1da4abaa4b97c628563b))
* **live2d:** wrong model size on mobile device full screen ([1ecafaa](https://github.com/Sekai-World/sekai-viewer/commits/1ecafaae19e1e882696289ea5be1e589999e8a97))
* **pwa:** update notification not shown in firefox ([09a1488](https://github.com/Sekai-World/sekai-viewer/commits/09a14887ff6fc5cb4c27edfc186feaf0fae09ecf))


### Refactors

* move spoiler tag inside image in grid view ([da1bcc2](https://github.com/Sekai-World/sekai-viewer/commits/da1bcc2086c6827b9850d7599e49bcc3aef56673))
* **annoucnement:** use created_at instead of published_at as publication time ([891a893](https://github.com/Sekai-World/sekai-viewer/commits/891a89388c02240f398fbc1a5df8755714876562))

### [0.3.1](https://github.com/Sekai-World/sekai-viewer/compare/v0.3.0...v0.3.1) (2021-01-16)


### Bug Fixes

* home screen white blank page bug ([a634397](https://github.com/Sekai-World/sekai-viewer/commits/a634397255e80b42ae5473142a95ea1a85d2bdd3))


### Refactors

* reduce load i18n json requests ([e6e26c4](https://github.com/Sekai-World/sekai-viewer/commits/e6e26c429fbcc5a50f75754aba28ec8058f713bd))

## [0.3.0](https://github.com/Sekai-World/sekai-viewer/compare/v0.2.2...v0.3.0) (2021-01-14)


### Features

* **announcement:** get by preferred languages ([83ce93d](https://github.com/Sekai-World/sekai-viewer/commits/83ce93ddf0931260784001b8d145f3854607fc37))
* **card:** add rarity filter for list ([5663d0d](https://github.com/Sekai-World/sekai-viewer/commits/5663d0dd73ab26f19cad57a5d3eb46a335dcddc3))
* **sw:** cache more resource ([bb8fffe](https://github.com/Sekai-World/sekai-viewer/commits/bb8fffe195feb3779f130e655a0ebf9ec9dcd625))
* **translate:** add language filters ([db7f1e6](https://github.com/Sekai-World/sekai-viewer/commits/db7f1e65ff9e4860e4781fa114ef4651c223a175))
* add honor title list page ([e68f498](https://github.com/Sekai-World/sekai-viewer/commits/e68f498912afbccfda62b9d39ace5c12e8a280ae))
* add main page skeleton to reduce white screen time ([c274215](https://github.com/Sekai-World/sekai-viewer/commits/c2742153ddf41447b17d4d4142d12eb91a570700))


### Bug Fixes

* **card:** comfy view text outside of box ([88ee74e](https://github.com/Sekai-World/sekai-viewer/commits/88ee74e27e542f97d512b2c4346306ee7cde041c))
* **mission:** character mission use translation strings ([35c4173](https://github.com/Sekai-World/sekai-viewer/commits/35c41733804a15e5655a4ebfe0e174dbb968bc89))
* **user:** restore bind sekai function ([d55ea15](https://github.com/Sekai-World/sekai-viewer/commits/d55ea15918e61cb6f8c768546ff877a8c16cfd65))


### Refactors

* **announcement:** remove author field ([8770428](https://github.com/Sekai-World/sekai-viewer/commits/8770428be2fcab71fcba4b1c0e27d6bbbd6d6702))
* import `useSWR`, remove refState for lists ([159d546](https://github.com/Sekai-World/sekai-viewer/commits/159d546e812c7ac728c12029c6dec5a4dcb11c3f))
* **home:** layout of links ([16fd1aa](https://github.com/Sekai-World/sekai-viewer/commits/16fd1aa250884f3f22a1b2b8706374a2958276a5))
* **music:** tag filter use chip instead of select ([7ba3f4c](https://github.com/Sekai-World/sekai-viewer/commits/7ba3f4c89d628bd04a01cf4c73427371c680ecdd))

### [0.2.2](https://github.com/Sekai-World/sekai-viewer/compare/v0.2.1...v0.2.2) (2021-01-10)


### Bug Fixes

* **mission:** beginner and normal mission reward icon strectched ([38e5b32](https://github.com/Sekai-World/sekai-viewer/commits/38e5b32eeffefc53e8d2a95f5a0240c50c9e56fb))
* **mission:** honor popup title translation ([5ff2250](https://github.com/Sekai-World/sekai-viewer/commits/5ff2250edb19f3aa4bdfb6ed63f2d790b507ebc4))
* **mission:** show honor group ([679ba58](https://github.com/Sekai-World/sekai-viewer/commits/679ba58b3adca97d943a2c43a6d3dfd77cd61c75))
* **storyreader:** story title translation ([e5b8fa7](https://github.com/Sekai-World/sekai-viewer/commits/e5b8fa7f0efc16d4f956540bce6943eeab28b351))
* **user:** profile page circular progress on submitting ([6ee764a](https://github.com/Sekai-World/sekai-viewer/commits/6ee764a6b2b90018d7243ffda51645bd8906d2f2))
*  avatar in usermeta could be null ([76f2870](https://github.com/Sekai-World/sekai-viewer/commits/76f2870448d1862ae45de1163fab2ae880a23ca9))


### Refactors

* **api:** sort languages by id asc ([c2bc965](https://github.com/Sekai-World/sekai-viewer/commits/c2bc965820fa0a9ef33e5e59237ccde7e034633d))
* **music:** music vocal type translation ([61578a8](https://github.com/Sekai-World/sekai-viewer/commits/61578a8708eb960bbff86cff3084dc54212ec53b))
* **virtual-live:** use accordion to replace collapse ([f1fa206](https://github.com/Sekai-World/sekai-viewer/commits/f1fa2062213411b30e5ce136c0fa34ae6737fc83))

### [0.2.1](https://github.com/Sekai-World/sekai-viewer/compare/v0.2.0...v0.2.1) (2021-01-10)


### Features

* **user:** allow user to edit preferred languages ([36ece0b](https://github.com/Sekai-World/sekai-viewer/commits/36ece0b9dd7b5465fb213996077ddcb06fbb57f5))


### Bug Fixes

* **announcement:** fetch only display language if not logged in ([36ad7a4](https://github.com/Sekai-World/sekai-viewer/commits/36ad7a49027e4b2bc96a7d3355f75d97215ef1c2))
* **gacha:** gacha simulator shows weird pull results ([4809029](https://github.com/Sekai-World/sekai-viewer/commits/4809029171071d8cb05493e6ed5689f39031b8db)), closes [#309](https://github.com/Sekai-World/sekai-viewer/issues/309)
* **widget:** set overflow to auto ([38cd6fe](https://github.com/Sekai-World/sekai-viewer/commits/38cd6fe19df41bb8cb991f0a833b09bc042d6d75))


### Refactors

* **user:** sekai profile to separate section ([16010c3](https://github.com/Sekai-World/sekai-viewer/commits/16010c32f713b8f2d2f39c97c38d092694362d5c))
