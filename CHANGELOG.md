# Changelog

## [2.5.0](https://github.com/alexvanderberkel/actions-template-sync/compare/v2.4.3...v2.5.0) (2025-01-20)


### Features

* **#586:** :sparkles: add option to sync within multiple orgs ([0a18296](https://github.com/alexvanderberkel/actions-template-sync/commit/0a182963a42ebad9e7645173326c0138835a88ce))
* add GitHub app testing workflow and integrate it into main workflow ([db0f8bb](https://github.com/alexvanderberkel/actions-template-sync/commit/db0f8bb2557de1da838aa182dbf837e60412c9aa))


### Bug Fixes

* add .git extension to source_repo_path in test_github_app.yml for consistency ([cda9f3d](https://github.com/alexvanderberkel/actions-template-sync/commit/cda9f3de65e0adfb14e0c9365c048c52566c1b27))
* add active authentication check and switch hostname in logout process in sync_template.sh ([2b6c8c6](https://github.com/alexvanderberkel/actions-template-sync/commit/2b6c8c65d78ed8a2cd52bbebf8cc672fe40714d4))
* add active authentication check before logout in sync_template.sh ([ad2c76c](https://github.com/alexvanderberkel/actions-template-sync/commit/ad2c76cb449fde4c1a5db2eb385df682c013355f))
* add authentication status check before logout in sync_template.sh ([79d929b](https://github.com/alexvanderberkel/actions-template-sync/commit/79d929b5e5775723b974db832990c117071d6579))
* add command to list organizations in sync_template.sh ([b59700f](https://github.com/alexvanderberkel/actions-template-sync/commit/b59700f68dbd7363703013e0774efac65ee83ed7))
* add command to list public repositories in sync_template.sh ([9c2842b](https://github.com/alexvanderberkel/actions-template-sync/commit/9c2842b6dca3980619e0629a4c3863fa5532facc))
* add command to list public repositories in sync_template.sh ([2684f15](https://github.com/alexvanderberkel/actions-template-sync/commit/2684f15680c93a35ccd1bd714cefd7d89d37fe29))
* add command to retrieve GitHub authentication token in sync_template.sh ([4eb0073](https://github.com/alexvanderberkel/actions-template-sync/commit/4eb007377d71c031cde82fcf24fd99f2f9732584))
* add completion log for variable initialization in sync_template.sh ([eb14149](https://github.com/alexvanderberkel/actions-template-sync/commit/eb141491dfe3315f9a6216921fa55fa0863efdb5))
* add gh auth switch command in git_init function for improved authentication handling ([cda8408](https://github.com/alexvanderberkel/actions-template-sync/commit/cda84086afdff484dbb1d7025009ba4574c1aeea))
* add gh_token parameter to test_github_app.yml workflow ([d71e92f](https://github.com/alexvanderberkel/actions-template-sync/commit/d71e92f3172ee26277733c097d5e8cb28b4ababc))
* add GitHub authentication command in entrypoint.sh for HTTPS protocol ([f9821dc](https://github.com/alexvanderberkel/actions-template-sync/commit/f9821dc51e9e1e743202208a3672aec2143b6de8))
* add GitHub authentication for source repository in entrypoint.sh ([40b1494](https://github.com/alexvanderberkel/actions-template-sync/commit/40b149401642d573c26c92e4c5cfca4661e6fa0f))
* add GitHub authentication status check in sync_template.sh ([cc00127](https://github.com/alexvanderberkel/actions-template-sync/commit/cc001273cddd6b7db30ebfdb29280d6b58eed372))
* add GitHub authentication status logging in sync_template.sh ([585583f](https://github.com/alexvanderberkel/actions-template-sync/commit/585583f9e871d99ba60e25770f0534249217a023))
* add GitHub status check before determining upstream branch in sync_template.sh ([d3e1b16](https://github.com/alexvanderberkel/actions-template-sync/commit/d3e1b1619573f90fef95776bf01e0b9006ce59f1))
* add informational messages for GitHub authentication in entrypoint.sh ([c86d904](https://github.com/alexvanderberkel/actions-template-sync/commit/c86d904832443c03b9bc9555b502961ba0da0d1f))
* add logging for SSH setup and source repo export in git_init function ([31155db](https://github.com/alexvanderberkel/actions-template-sync/commit/31155db578fc6f5a78a591bf09e915cfb14381c1))
* add logging for unset GITHUB_TOKEN and completion of git global configuration in git_init function of entrypoint.sh ([8af787b](https://github.com/alexvanderberkel/actions-template-sync/commit/8af787bec0e530cbcc34efa5d837281e9579024a))
* add login confirmation message in sync_template.sh after authentication ([7320bd1](https://github.com/alexvanderberkel/actions-template-sync/commit/7320bd126bb9baf1aaa361a38f649ad228b3e1b1))
* add logout command for source repository in sync_template.sh before target login ([fce707b](https://github.com/alexvanderberkel/actions-template-sync/commit/fce707b507065f6180981f36c5dc12d53c91bf5e))
* add private repository to the list of repositories in test_github_app.yml ([4cc5b1f](https://github.com/alexvanderberkel/actions-template-sync/commit/4cc5b1f36ebc0ec364e5dfc179a7a3e75f568321))
* add repository existence check in sync_template.sh ([476bb32](https://github.com/alexvanderberkel/actions-template-sync/commit/476bb32b78ab488b24bfc13376e9dfbf6b32682c))
* add repository view command in sync_template.sh ([11a333d](https://github.com/alexvanderberkel/actions-template-sync/commit/11a333d44c1bba4ba28b1bf7c3b5b9ade8f43370))
* add session check before logout in sync_template.sh for source repository ([4aab3cb](https://github.com/alexvanderberkel/actions-template-sync/commit/4aab3cb1fa368790c1544271abcfd02d0ab611a9))
* add TARGET_GH_TOKEN authentication in git_init function of entrypoint.sh for improved functionality ([e1f7ad7](https://github.com/alexvanderberkel/actions-template-sync/commit/e1f7ad7ae457f757185b38be8c63440e7afb3c1f))
* add target_gh_token parameter to test.yml workflow ([6087400](https://github.com/alexvanderberkel/actions-template-sync/commit/6087400d643112c485de4de06f7c26d4fc36eca0))
* add user login retrieval in git_init function of entrypoint.sh ([55f7ec3](https://github.com/alexvanderberkel/actions-template-sync/commit/55f7ec3fb9a29e4d9050f27fe946253f8c8e050a))
* change log message for missing TARGET_GH_TOKEN and improve authentication handling in git_init function ([bbe7b31](https://github.com/alexvanderberkel/actions-template-sync/commit/bbe7b31e9ec99ea94c4035ae411b497ba39ea646))
* change visibility option to list private repositories in sync_template.sh ([b21d92a](https://github.com/alexvanderberkel/actions-template-sync/commit/b21d92a6d7e80ec73ec743973c72729ea3e32506))
* clean up entrypoint.sh and sync_template.sh by removing unnecessary logging and improving token handling ([1c62295](https://github.com/alexvanderberkel/actions-template-sync/commit/1c6229561c0cce2d3989d040fdbaf5c8824f8d1d))
* clear default value for target_gh_token in action.yml ([9189e8d](https://github.com/alexvanderberkel/actions-template-sync/commit/9189e8d4cc5e7113fedfe23256acbb4c721c7bde))
* clear GH_TOKEN before logging into the target in sync_template.sh ([427999b](https://github.com/alexvanderberkel/actions-template-sync/commit/427999bd5ac0e70cf5d2f114c65af2283e2d6dd7))
* correct command to check active authentication status in sync_template.sh ([f1313f1](https://github.com/alexvanderberkel/actions-template-sync/commit/f1313f1b54670a7e2a1e5e2fe0ba7076588225de))
* correct GitHub logout command syntax in entrypoint.sh ([52b3ad5](https://github.com/alexvanderberkel/actions-template-sync/commit/52b3ad5a5701ec6be448f770bd4c3dbe7fcaec77))
* correct logging message for initial steps in sync_template.sh ([cfc2560](https://github.com/alexvanderberkel/actions-template-sync/commit/cfc2560fab7ecb627ccf389c32d54fd6191da6fb))
* correct syntax error in authentication switch command in sync_template.sh ([50c8e06](https://github.com/alexvanderberkel/actions-template-sync/commit/50c8e06ebb4beadae13c87592a802c53da5e5e32))
* correct syntax for exporting GitHub token in sync_template.sh ([58030b0](https://github.com/alexvanderberkel/actions-template-sync/commit/58030b056279a44b70d81a69f996d822dbde82fb))
* correct syntax for GitHub logout command in entrypoint.sh ([29aeaf9](https://github.com/alexvanderberkel/actions-template-sync/commit/29aeaf9f666a3a40d67a3fbfc20f94f016eab8c8))
* enhance authentication flow by setting TARGET_GH_TOKEN and adding logout command in entrypoint.sh and sync_template.sh ([16fa497](https://github.com/alexvanderberkel/actions-template-sync/commit/16fa497a9cbdfc317479c6aaad43d510af55dec9))
* enhance git authentication handling in git_init function for non-default repository hosts ([e669321](https://github.com/alexvanderberkel/actions-template-sync/commit/e66932117bcdd75b6f61466c633ac17e7f6cb93d))
* ensure GITHUB_TOKEN is checked before logging into the source repository in entrypoint.sh ([f13350e](https://github.com/alexvanderberkel/actions-template-sync/commit/f13350edb87344d929e863aa0676e683dffec001))
* improve git authentication handling in git_init function for target repository ([ba90628](https://github.com/alexvanderberkel/actions-template-sync/commit/ba9062818a73ef00abcb66f0de9e2622bc466a44))
* improve token handling in sync_template.sh by using here-string for authentication ([86074f5](https://github.com/alexvanderberkel/actions-template-sync/commit/86074f5a54211d4d05d3ca67e9e6e412850b3b18))
* log the TARGET_GH_TOKEN after storing it in entrypoint.sh ([be29680](https://github.com/alexvanderberkel/actions-template-sync/commit/be29680976467fa5773f04572df4de4fdf3280f6))
* make target_gh_token input required in action.yml and add it to test_github_app.yml workflow ([bc6da9f](https://github.com/alexvanderberkel/actions-template-sync/commit/bc6da9fa49ed3dd20729e741e9decafd4c825346))
* make target_gh_token parameter required in action.yml ([2060613](https://github.com/alexvanderberkel/actions-template-sync/commit/2060613464a42b07e97be0d984ae50d46dd6e2e2))
* remove .git extension from source_repo_path in test_github_app.yml for consistency ([2248ba5](https://github.com/alexvanderberkel/actions-template-sync/commit/2248ba5a34f54b456a7ea2bcb4863cc5874c0aff))
* remove check for missing GITHUB_TOKEN in entrypoint.sh ([1c59e5f](https://github.com/alexvanderberkel/actions-template-sync/commit/1c59e5f555c1a3d96e240281bbbf18e459972fb8))
* remove duplicate github_token parameter in test_github_app.yml workflow ([37f17ad](https://github.com/alexvanderberkel/actions-template-sync/commit/37f17adb027b1f82c3d32e6b0e7082f8367e63ae))
* remove GH_TOKEN check and add gh auth switch command in sync_template.sh for improved authentication flow ([eba545b](https://github.com/alexvanderberkel/actions-template-sync/commit/eba545bc50d821bde5e94ee11e0f919a963d820d))
* remove logout command from sync_template.sh before logging into the target ([a17674c](https://github.com/alexvanderberkel/actions-template-sync/commit/a17674ce9d827d6e24786c072b21be45f06a6b7a))
* remove public-resources from repositories list in test_github_app.yml ([5618c2b](https://github.com/alexvanderberkel/actions-template-sync/commit/5618c2b8c47a61281cc8727749a771d069777320))
* remove redundant GH_TOKEN export in sync_template.sh ([1625bef](https://github.com/alexvanderberkel/actions-template-sync/commit/1625befae2ac3aabb96ebe016ce52893c57afbe0))
* remove redundant GITHUB_TOKEN check in git_init function of entrypoint.sh ([53da137](https://github.com/alexvanderberkel/actions-template-sync/commit/53da137a3eedb1ed5fbb25a3d11a4d7fa59e56b9))
* remove redundant unset of GITHUB_TOKEN before logging into the source repository in entrypoint.sh ([225b28e](https://github.com/alexvanderberkel/actions-template-sync/commit/225b28efd1ffdc852d6170385fdf127172799128))
* remove target_gh_token from test.yml workflow and update action.yml description ([8d334e1](https://github.com/alexvanderberkel/actions-template-sync/commit/8d334e155b139c9a7606529767a508fe4c2b9272))
* remove unnecessary GitHub status check and add completion log in sync_template.sh ([03c918f](https://github.com/alexvanderberkel/actions-template-sync/commit/03c918fce665406030ca77a6635c14d1a146810f))
* remove user login retrieval and logout command from git_init function in entrypoint.sh ([c557f83](https://github.com/alexvanderberkel/actions-template-sync/commit/c557f838419924d23a207ce33dd19a7fa2e4374b))
* rename gh_token parameter to github_token in test_github_app.yml workflow ([c7ca24a](https://github.com/alexvanderberkel/actions-template-sync/commit/c7ca24a0dd6c1f6ca88f83264fd84cfc85e41800))
* rename gh_token to target_gh_token for consistency across workflows and update action.yml ([46e3ff0](https://github.com/alexvanderberkel/actions-template-sync/commit/46e3ff054c8a834cc0dab3a26267aa0a4bd29d0c))
* rename github_token to source_gh_token and add target_gh_token in action.yml for clarity ([a99a014](https://github.com/alexvanderberkel/actions-template-sync/commit/a99a0142991ae0935cdf33b222339df8d27a2b0d))
* rename github_token to target_gh_token in workflow and action files; update entrypoint.sh for token handling ([c7506b5](https://github.com/alexvanderberkel/actions-template-sync/commit/c7506b5ba900cc610693e824421035a9660cc287))
* rename source_github_token to source_gh_token and add target_gh_token in workflows; update entrypoint.sh for token usage ([7acf15c](https://github.com/alexvanderberkel/actions-template-sync/commit/7acf15c83cf16ce732f24af09c9695919f6a3070))
* rename SOURCE_REPO_GITHUB_TOKEN to SOURCE_GH_TOKEN in entrypoint.sh for consistency ([5f36f51](https://github.com/alexvanderberkel/actions-template-sync/commit/5f36f51c58de872c8f936c8631287d0a6b6c5181))
* rename target_gh_token to gh_token for consistency and update related workflows ([ee0df23](https://github.com/alexvanderberkel/actions-template-sync/commit/ee0df2306d2749ea725cecb4c7cbbea78ba901a0))
* rename target_gh_token to target_token in action.yml and set default to github.token ([dac3e2c](https://github.com/alexvanderberkel/actions-template-sync/commit/dac3e2ced6801d3d5218f8d92ea61ca69ada12b6))
* rename target_gh_token to target_token in action.yml for consistency ([e916951](https://github.com/alexvanderberkel/actions-template-sync/commit/e916951ebf3d7575790aca4d942b3b818e5b8be0))
* rename target_github_token to source_github_token in action.yml and update authentication logic in entrypoint.sh ([b037fc1](https://github.com/alexvanderberkel/actions-template-sync/commit/b037fc1256ef3ec056fff50e4374c3ec0b5117e2))
* reorder authentication commands in sync_template.sh for improved logic flow ([ed67a3a](https://github.com/alexvanderberkel/actions-template-sync/commit/ed67a3af255d8a3001d18cbf1ba405cfce7fb59a))
* reorder git authentication setup in git_init function for clarity ([97832d0](https://github.com/alexvanderberkel/actions-template-sync/commit/97832d028f03afd2ddb988fb8e0f62d4568b58f2))
* set GitHub token environment variable in sync_template.sh ([06b2906](https://github.com/alexvanderberkel/actions-template-sync/commit/06b2906f19bd89031cd0770e48fdd88d371f3598))
* set TARGET_GH_TOKEN before logging into the source repository in entrypoint.sh ([0e00dc6](https://github.com/alexvanderberkel/actions-template-sync/commit/0e00dc655c0f6847fa40716040e5498d89f6905d))
* simplify authentication command in entrypoint.sh by removing token input ([8af40d3](https://github.com/alexvanderberkel/actions-template-sync/commit/8af40d319f224d07b6568503a4e91d9ca9076ed6))
* simplify authentication in sync_template.sh by removing redundant login command and using gh auth switch ([af22ad0](https://github.com/alexvanderberkel/actions-template-sync/commit/af22ad06e6badacfe0f286241465392c500c6fbd))
* simplify logout command in sync_template.sh by removing hostname parameter ([b77df42](https://github.com/alexvanderberkel/actions-template-sync/commit/b77df422c01dd88e38ad9d938f9f26c1c4f2dacb))
* simplify logout command in sync_template.sh for source repository ([542986e](https://github.com/alexvanderberkel/actions-template-sync/commit/542986e75c6747c11d22c380bb34f11e536ac1f2))
* specify hostname for GitHub logout command in entrypoint.sh ([c4476ac](https://github.com/alexvanderberkel/actions-template-sync/commit/c4476acf2dbff63e66a1fd85ea746736f8e53392))
* standardize token variable name to github_token in workflow files and entrypoint script ([5bd6a4e](https://github.com/alexvanderberkel/actions-template-sync/commit/5bd6a4e200aabe452103cc42f83b01d0dd17b47b))
* store TARGET_GH_TOKEN in entrypoint.sh before accessing the source repository ([3a7dd31](https://github.com/alexvanderberkel/actions-template-sync/commit/3a7dd31f4be0c195935d1fbed7ddd44f8d043f2b))
* streamline authentication checks in sync_template.sh by removing redundant login commands ([46d6bdf](https://github.com/alexvanderberkel/actions-template-sync/commit/46d6bdfea2e804b9dc20fb6d990596f600e0ed51))
* streamline authentication in sync_template.sh by removing unnecessary logout and enhancing login with token handling ([3b70ee0](https://github.com/alexvanderberkel/actions-template-sync/commit/3b70ee08b790ab8e84d636f787a24cd0ec2a476a))
* streamline authentication process by removing redundant gh auth status calls ([e1b3e08](https://github.com/alexvanderberkel/actions-template-sync/commit/e1b3e08b3de9514cca35faaf2804b7a1f5da9c0f))
* streamline git authentication process in git_init function ([a85bec5](https://github.com/alexvanderberkel/actions-template-sync/commit/a85bec5be54036b4901e5e8e92279c7ba5224865))
* streamline git authentication process in git_init function of entrypoint.sh for improved clarity ([4623e44](https://github.com/alexvanderberkel/actions-template-sync/commit/4623e44e69a232313de1ab31b429afeaf1529ffa))
* streamline git initialization logging and add precheck confirmation ([680446c](https://github.com/alexvanderberkel/actions-template-sync/commit/680446c1a44462590333c9bacdd1229214942412))
* streamline logout process in sync_template.sh by removing session check ([df8e524](https://github.com/alexvanderberkel/actions-template-sync/commit/df8e524007b6cd3f7b6bc9935a4a55321186bd11))
* unset GH_TOKEN before exporting new value in sync_template.sh ([4691f0e](https://github.com/alexvanderberkel/actions-template-sync/commit/4691f0e836c91f0602beb540e1f3566c2f23cebb))
* unset GH_TOKEN before logging into the source repository ([66547e7](https://github.com/alexvanderberkel/actions-template-sync/commit/66547e71a2121eeecefb7c29b023662c92e97877))
* unset GITHUB_TOKEN before GitHub authentication in entrypoint.sh ([1b1c87a](https://github.com/alexvanderberkel/actions-template-sync/commit/1b1c87ab711a08e52ebf744981f860266035a540))
* unset GITHUB_TOKEN before GitHub login in git_init function of entrypoint.sh ([22dd7ed](https://github.com/alexvanderberkel/actions-template-sync/commit/22dd7edf8e9465ec2cd42dfb1f1f270233d25f9f))
* unset GITHUB_TOKEN before logging into the source repository ([37c0c84](https://github.com/alexvanderberkel/actions-template-sync/commit/37c0c84baab638e63f7e3bfdde5358ea9351cfe6))
* unset GITHUB_TOKEN before logging into the source repository in entrypoint.sh ([331b2f2](https://github.com/alexvanderberkel/actions-template-sync/commit/331b2f286eba18f649cd637ed869744e7efbc3be))
* update action.yml description for github_token and clean up entrypoint.sh and sync_template.sh by removing unnecessary logout command ([98a77bd](https://github.com/alexvanderberkel/actions-template-sync/commit/98a77bda082eb1a847237d8822d42c3dfd128061))
* update authentication command to use TARGET_GH_TOKEN for login in sync_template.sh ([235b7ac](https://github.com/alexvanderberkel/actions-template-sync/commit/235b7ac4ca325235965d046f89f30e82a8fe0757))
* update authentication in sync_template.sh to use DEFAULT_REPO_HOSTNAME for target login ([c141df7](https://github.com/alexvanderberkel/actions-template-sync/commit/c141df71d88d22e1aec64b96db2cdc31cc12239f))
* update authentication in sync_template.sh to use dynamic hostname for target login ([ee9aec8](https://github.com/alexvanderberkel/actions-template-sync/commit/ee9aec868f7cca5808930b7d9d6aa9b593594efb))
* update authentication in sync_template.sh to use GITHUB_SERVER_URL instead of DEFAULT_REPO_HOSTNAME ([80363f9](https://github.com/alexvanderberkel/actions-template-sync/commit/80363f9aace01f93ad329d47b3575ee08ae23463))
* update authentication in sync_template.sh to use HOSTNAME for target login ([6d42938](https://github.com/alexvanderberkel/actions-template-sync/commit/6d4293804625cc9c1ce9272d972b0529c8a0a12d))
* update authentication in sync_template.sh to use specific hostname for target login ([0ad8dae](https://github.com/alexvanderberkel/actions-template-sync/commit/0ad8dae7e5718ede07e32b852bea2c324e77a129))
* update authentication logic in pull_source_changes function to check for SOURCE_GH_TOKEN ([594b2f1](https://github.com/alexvanderberkel/actions-template-sync/commit/594b2f11463d29959a4ae25668f5ab8022e8aaa8))
* update authentication login command to use fixed hostname in sync_template.sh ([56802af](https://github.com/alexvanderberkel/actions-template-sync/commit/56802af1099d4609e23c18f32c138681fc9662f1))
* update authentication switch command to use GITHUB_SERVER_URL in sync_template.sh ([1fa5a35](https://github.com/alexvanderberkel/actions-template-sync/commit/1fa5a35fea682e3120de1e79705c6a30615231c5))
* update command to check active GitHub authentication status in sync_template.sh ([99b5096](https://github.com/alexvanderberkel/actions-template-sync/commit/99b5096253aecfa0adb89ad448c61abb88baf796))
* update default token format in action.yml and add log message in entrypoint.sh ([cc77202](https://github.com/alexvanderberkel/actions-template-sync/commit/cc77202027265886368f4cb7fd006c6cad61d4fd))
* update default value for source_gh_token in action.yml to use github.token ([d460325](https://github.com/alexvanderberkel/actions-template-sync/commit/d460325e4d725b7ea6bc87f2c2399654ab0c8b9e))
* update default value for target_gh_token in action.yml and add authentication status check in git_init function of entrypoint.sh ([1113dcc](https://github.com/alexvanderberkel/actions-template-sync/commit/1113dcc58df922022349335d659baec8c0a317e8))
* update default value for target_gh_token in action.yml to use github.token for improved security ([585bae1](https://github.com/alexvanderberkel/actions-template-sync/commit/585bae12bf2ede0ac495f7a25dbf93ff8505756f))
* update entrypoint.sh to use GITHUB_TOKEN for authentication when TARGET_GH_TOKEN is not set ([154fc50](https://github.com/alexvanderberkel/actions-template-sync/commit/154fc505306fb9c01e8d6eb81093f9d3386dfdaf))
* update error message for missing source_github_token in entrypoint.sh ([3592a11](https://github.com/alexvanderberkel/actions-template-sync/commit/3592a11fbbd879e91c0b0aec9bfb75a492615298))
* update git authentication flow in git_init function of entrypoint.sh for improved clarity and functionality ([6469e36](https://github.com/alexvanderberkel/actions-template-sync/commit/6469e36e0f228dbbc7f51ca8d85382eab54a75e0))
* update GitHub app token secrets in test workflow ([ae538c0](https://github.com/alexvanderberkel/actions-template-sync/commit/ae538c0fd7e4525068ef2d8543528baff0aaa1f3))
* update GitHub authentication flow in entrypoint.sh to include logout before login ([e44a2fa](https://github.com/alexvanderberkel/actions-template-sync/commit/e44a2fa7a5ac9bc59c64d5f8e83625e47e3cd2dd))
* update GitHub token variable in entrypoint.sh for authentication ([b09587f](https://github.com/alexvanderberkel/actions-template-sync/commit/b09587f84172f00b9a094fb46937b595af264115))
* update logging for initial steps in sync_template.sh ([46d6e45](https://github.com/alexvanderberkel/actions-template-sync/commit/46d6e45f88399bfdec61d657270335185338b342))
* update logout command in sync_template.sh to use GITHUB_SERVER_URL ([fabb9bc](https://github.com/alexvanderberkel/actions-template-sync/commit/fabb9bc632c5ed5389ab881e59ad3576a748da49))
* update logout command to use GITHUB_SERVER_URL in sync_template.sh ([3d9bd0e](https://github.com/alexvanderberkel/actions-template-sync/commit/3d9bd0e4a9bd68281a5a88af80545615a522ba16))
* update logout command to use login with token in sync_template.sh ([b523a02](https://github.com/alexvanderberkel/actions-template-sync/commit/b523a023123cf1786704f75682f85b3b46862c70))
* update logout command to use SOURCE_REPO_HOSTNAME in sync_template.sh ([7717af9](https://github.com/alexvanderberkel/actions-template-sync/commit/7717af99f3994644573a21e80a535fbc7a696913))
* update logout process in sync_template.sh to specify user for logout command ([6ccb0af](https://github.com/alexvanderberkel/actions-template-sync/commit/6ccb0af5753bdff298a6cb68e0423a5156d11806))
* update repository variable in sync_template.sh for dynamic access ([0d0c844](https://github.com/alexvanderberkel/actions-template-sync/commit/0d0c844c2d36efde91ae83bb4d23d93c6e17e09a))
* update source repository path in GitHub Actions workflow ([3e5c181](https://github.com/alexvanderberkel/actions-template-sync/commit/3e5c1818e0f935c9d382c1ffd2412395d7eebad1))
* update source repository path in test workflow ([117f999](https://github.com/alexvanderberkel/actions-template-sync/commit/117f99909f2c57f6a3b69d9a5a1dba40c400bf7b))
* update source repository path in test_github_app.yml for consistency ([06b1fd7](https://github.com/alexvanderberkel/actions-template-sync/commit/06b1fd71e7cb95de57dc2e716e4ad80f2b782a9d))
* update SOURCE_GH_TOKEN references in action.yml and entrypoint.sh for consistency ([6c927b4](https://github.com/alexvanderberkel/actions-template-sync/commit/6c927b43ce8e43b930113cb5b1c29806e907c81c))
* update source_github_token to source_g_token in action.yml and enhance git_init function in entrypoint.sh for improved authentication flow ([4608610](https://github.com/alexvanderberkel/actions-template-sync/commit/4608610556e76005d85ea2152a6370fab76f772d))
* update target_gh_token input in action.yml to be optional and adjust workflow token usage for consistency ([e597db8](https://github.com/alexvanderberkel/actions-template-sync/commit/e597db8bb77e0327289af5da60079d806393ddda))
* update TARGET_GH_TOKEN reference in action.yml to use inputs.target_gh_token for consistency ([84cf659](https://github.com/alexvanderberkel/actions-template-sync/commit/84cf65918662056f07f9811063395d27af2af0d2))
* update token references in workflows and action.yml for consistency and clarity ([c76ac6d](https://github.com/alexvanderberkel/actions-template-sync/commit/c76ac6d6b01be8c5e773dd1a6f8195ad8a193ad2))
* update variable name from TARGET_GH_TOKEN to GITHUB_TOKEN in action.yml ([9bef0a6](https://github.com/alexvanderberkel/actions-template-sync/commit/9bef0a60979b07d7be6ac5af1e85dd5378513278))
* update variable name from TARGET_GH_TOKEN to GITHUB_TOKEN in entrypoint.sh ([0be95b2](https://github.com/alexvanderberkel/actions-template-sync/commit/0be95b2b22beff1265178b55a3b2cb82cbd9e80d))
* update workflow files and action.yml to use target_gh_token instead of github_token ([7b81085](https://github.com/alexvanderberkel/actions-template-sync/commit/7b81085e0bf926012a3f591c7bfb771a07663edf))

## [2.4.2](https://github.com/AndreasAugustin/actions-template-sync/compare/v2.4.1...v2.4.2) (2025-01-07)


### Bug Fixes

* **#551:** fix issue with file deletion ([#596](https://github.com/AndreasAugustin/actions-template-sync/issues/596)) ([1641155](https://github.com/AndreasAugustin/actions-template-sync/commit/164115568a2f8a4ea67dda06f786a9c90624971d))
* **#591:** add missing gh cli precheck ([#594](https://github.com/AndreasAugustin/actions-template-sync/issues/594)) ([574812a](https://github.com/AndreasAugustin/actions-template-sync/commit/574812a4ea91dcaa3ffe39ace616fd329b209e43))

## [2.4.1](https://github.com/AndreasAugustin/actions-template-sync/compare/v2.4.0...v2.4.1) (2024-10-15)


### Bug Fixes

* incorrect argument passing to git push ([#574](https://github.com/AndreasAugustin/actions-template-sync/issues/574)) ([44e59ba](https://github.com/AndreasAugustin/actions-template-sync/commit/44e59ba38bf03b73ddf96462365826b01cf7f1b8))

## [2.4.0](https://github.com/AndreasAugustin/actions-template-sync/compare/v2.3.0...v2.4.0) (2024-10-15)


### Features

* **#567:** Add the name of the .templatesyncignore file as a parameter  ([#568](https://github.com/AndreasAugustin/actions-template-sync/issues/568)) ([03661a8](https://github.com/AndreasAugustin/actions-template-sync/commit/03661a8560de11c0fb0203642f69799f481286bd))

## [2.3.0](https://github.com/AndreasAugustin/actions-template-sync/compare/v2.2.3...v2.3.0) (2024-10-14)


### Features

* **#547:** :sparkles: add option to include git tags ([#561](https://github.com/AndreasAugustin/actions-template-sync/issues/561)) ([01f7623](https://github.com/AndreasAugustin/actions-template-sync/commit/01f7623dbfc8f73ccaf1635d64cb629a699acc9a))

## [2.2.3](https://github.com/AndreasAugustin/actions-template-sync/compare/v2.2.2...v2.2.3) (2024-06-19)


### Bug Fixes

* **#536:** :bug: issue with comments within .templatesyncignore ([#538](https://github.com/AndreasAugustin/actions-template-sync/issues/538)) ([aba0971](https://github.com/AndreasAugustin/actions-template-sync/commit/aba0971640d113cd858cfbb6b9eb2f4c2de09049))

## [2.2.2](https://github.com/AndreasAugustin/actions-template-sync/compare/v2.2.1...v2.2.2) (2024-06-16)


### Bug Fixes

* **#529:** :bug: edge case with branch cleanup and force push ([#534](https://github.com/AndreasAugustin/actions-template-sync/issues/534)) ([ab9498f](https://github.com/AndreasAugustin/actions-template-sync/commit/ab9498f63d0cf03e677228c6a2f6828adf8b4662))

## [2.2.1](https://github.com/AndreasAugustin/actions-template-sync/compare/v2.2.0...v2.2.1) (2024-06-06)


### Bug Fixes

* **#528:** :memo: small docs update ([4eb71ce](https://github.com/AndreasAugustin/actions-template-sync/commit/4eb71ce2acda4476ed387a8b42cd94846ca8474e))

## [2.2.0](https://github.com/AndreasAugustin/actions-template-sync/compare/v2.1.0...v2.2.0) (2024-05-27)


### Features

* **#523:** :sparkles: delete branches on pr cleanup ([#525](https://github.com/AndreasAugustin/actions-template-sync/issues/525)) ([d957348](https://github.com/AndreasAugustin/actions-template-sync/commit/d9573484779def3582a6d442502aaa69eaf674e9))

## [2.1.0](https://github.com/AndreasAugustin/actions-template-sync/compare/v2.0.2...v2.1.0) (2024-04-23)


### Features

* **#478:** :sparkles: possible to execute single steps ([#516](https://github.com/AndreasAugustin/actions-template-sync/issues/516)) ([6b9bd88](https://github.com/AndreasAugustin/actions-template-sync/commit/6b9bd8844d2a75ecf2f4d2688b7f847fd86cffa3))

## [2.0.2](https://github.com/AndreasAugustin/actions-template-sync/compare/v2.0.1...v2.0.2) (2024-03-28)


### Bug Fixes

* **#510:** :bug: issue with blank lines within .templatesyncignore ([#512](https://github.com/AndreasAugustin/actions-template-sync/issues/512)) ([814f456](https://github.com/AndreasAugustin/actions-template-sync/commit/814f4564aa1ce6d354dcf48a34ea5b7a670327a5))

## [2.0.1](https://github.com/AndreasAugustin/actions-template-sync/compare/v2.0.0...v2.0.1) (2024-03-18)


### Bug Fixes

* **#507:** :bug: pr title and body internal variable substitution ([#508](https://github.com/AndreasAugustin/actions-template-sync/issues/508)) ([912b4e0](https://github.com/AndreasAugustin/actions-template-sync/commit/912b4e01a39729b00a1f928303f864294d6cbede))

## [2.0.0](https://github.com/AndreasAugustin/actions-template-sync/compare/v1.12.0...v2.0.0) (2024-03-13)


### ⚠ BREAKING CHANGES

* :sparkles: migrate from docker action to composite action  ([#498](https://github.com/AndreasAugustin/actions-template-sync/issues/498))

### Features

* :sparkles: migrate from docker action to composite action  ([#498](https://github.com/AndreasAugustin/actions-template-sync/issues/498)) ([29d0434](https://github.com/AndreasAugustin/actions-template-sync/commit/29d04342d0bd6047538dd7f52a7e64a8ca2d4baa))

## [1.12.0](https://github.com/AndreasAugustin/actions-template-sync/compare/v1.11.0...v1.12.0) (2024-03-13)


### Features

* **#482:** :sparkles: add option to force push and pr ([#499](https://github.com/AndreasAugustin/actions-template-sync/issues/499)) ([cbef7ee](https://github.com/AndreasAugustin/actions-template-sync/commit/cbef7ee63378db46e59d89a09c055376dccf4817))

## [1.11.0](https://github.com/AndreasAugustin/actions-template-sync/compare/v1.10.0...v1.11.0) (2024-03-11)


### Features

* :sparkles: gpg sign with passphrase ([#460](https://github.com/AndreasAugustin/actions-template-sync/issues/460)) ([cec582e](https://github.com/AndreasAugustin/actions-template-sync/commit/cec582ee2fc98db86d2cb5335a33a2fdaa59f418))

## [1.10.0](https://github.com/AndreasAugustin/actions-template-sync/compare/v1.9.0...v1.10.0) (2024-03-05)


### Features

* **#467:** :sparkles: hooks now within action inputs ([#489](https://github.com/AndreasAugustin/actions-template-sync/issues/489)) ([0e55c08](https://github.com/AndreasAugustin/actions-template-sync/commit/0e55c08f95f9a83c60f809fa6b49785187ec7623))

## [1.9.0](https://github.com/AndreasAugustin/actions-template-sync/compare/v1.8.1...v1.9.0) (2024-03-05)


### Features

* :sparkles: Set token to the default provided by GitHub workflow ([#483](https://github.com/AndreasAugustin/actions-template-sync/issues/483)) ([c1e7561](https://github.com/AndreasAugustin/actions-template-sync/commit/c1e756148de0343df66fda1a2380382ef06c16d7))
* **#477:** :sparkles: add input parameter for pr body ([#488](https://github.com/AndreasAugustin/actions-template-sync/issues/488)) ([481cc21](https://github.com/AndreasAugustin/actions-template-sync/commit/481cc21550d858dfc12c49f4dfb7605ac744a091))

## [1.8.1](https://github.com/AndreasAugustin/actions-template-sync/compare/v1.8.0...v1.8.1) (2024-03-02)


### Bug Fixes

* **#476:** :bug: output variable edge cases ([#479](https://github.com/AndreasAugustin/actions-template-sync/issues/479)) ([ab4153b](https://github.com/AndreasAugustin/actions-template-sync/commit/ab4153bb937a2d7ad996f0693977cb943443e8b3))

## [1.8.0](https://github.com/AndreasAugustin/actions-template-sync/compare/v1.7.0...v1.8.0) (2024-02-29)


### Features

* **#472:** :sparkles: define output ([#473](https://github.com/AndreasAugustin/actions-template-sync/issues/473)) ([a19cd8d](https://github.com/AndreasAugustin/actions-template-sync/commit/a19cd8d7c999cdf9bdc2a08818eb2878d1222cdf))

## [1.7.0](https://github.com/AndreasAugustin/actions-template-sync/compare/v1.6.2...v1.7.0) (2024-02-29)


### Features

* **#468:** :sparkles: enable usage of github env variables within hooks ([#469](https://github.com/AndreasAugustin/actions-template-sync/issues/469)) ([17d4603](https://github.com/AndreasAugustin/actions-template-sync/commit/17d4603da56b49e4b72c6531ba6d2db6dbcc3a31))

## [1.6.2](https://github.com/AndreasAugustin/actions-template-sync/compare/v1.6.1...v1.6.2) (2024-02-25)


### Bug Fixes

* :bug: try catch for edge cases ([#465](https://github.com/AndreasAugustin/actions-template-sync/issues/465)) ([95ce4e4](https://github.com/AndreasAugustin/actions-template-sync/commit/95ce4e4d5cc72b62970056977256a6592a10547c))

## [1.6.1](https://github.com/AndreasAugustin/actions-template-sync/compare/v1.6.0...v1.6.1) (2024-02-25)


### Bug Fixes

* **#461:** :bug: issue with pull request labels with emoji and space ([#462](https://github.com/AndreasAugustin/actions-template-sync/issues/462)) ([89b8d21](https://github.com/AndreasAugustin/actions-template-sync/commit/89b8d210b8454957a81dbbf5b81e6977708a25cd))

## [1.6.0](https://github.com/AndreasAugustin/actions-template-sync/compare/v1.5.0...v1.6.0) (2024-02-22)


### Features

* :sparkles: ([#204](https://github.com/AndreasAugustin/actions-template-sync/issues/204)) gpg sign ([#436](https://github.com/AndreasAugustin/actions-template-sync/issues/436)) ([99aefe5](https://github.com/AndreasAugustin/actions-template-sync/commit/99aefe5830f9ee249bbfbd90a85108f76e897c33))

## [1.5.0](https://github.com/AndreasAugustin/actions-template-sync/compare/v1.4.0...v1.5.0) (2024-02-04)


### Features

* :sparkles: ([#401](https://github.com/AndreasAugustin/actions-template-sync/issues/401)) add option to force file deletion ([#435](https://github.com/AndreasAugustin/actions-template-sync/issues/435)) ([e68941f](https://github.com/AndreasAugustin/actions-template-sync/commit/e68941ff0fc9695be3fe480ab739ebeb318dca0d))

## [1.4.0](https://github.com/AndreasAugustin/actions-template-sync/compare/v1.3.0...v1.4.0) (2024-01-25)


### Features

* allow for pruning of older PRs ([#438](https://github.com/AndreasAugustin/actions-template-sync/issues/438)) ([0e51714](https://github.com/AndreasAugustin/actions-template-sync/commit/0e51714bd42e4ce8223a641d7435c220a99aad51))

## [1.3.0](https://github.com/AndreasAugustin/actions-template-sync/compare/v1.2.0...v1.3.0) (2024-01-18)


### Features

* **hooks:** added precommit hook ([#439](https://github.com/AndreasAugustin/actions-template-sync/issues/439)) ([4a42410](https://github.com/AndreasAugustin/actions-template-sync/commit/4a42410a3c63b359844b20860359bc2f8ab4e6fa))

## [1.2.0](https://github.com/AndreasAugustin/actions-template-sync/compare/v1.1.9...v1.2.0) (2024-01-06)


### Features

* :construction_worker: ([#432](https://github.com/AndreasAugustin/actions-template-sync/issues/432)) support major/minor tags ([#433](https://github.com/AndreasAugustin/actions-template-sync/issues/433)) ([eb942cf](https://github.com/AndreasAugustin/actions-template-sync/commit/eb942cf9366ff4cfbcb6860f9392db555a4e5c11))

## [1.1.9](https://github.com/AndreasAugustin/actions-template-sync/compare/v1.1.8...v1.1.9) (2023-12-30)


### Bug Fixes

* github pat in documentation examples ([#423](https://github.com/AndreasAugustin/actions-template-sync/issues/423)) ([aea6128](https://github.com/AndreasAugustin/actions-template-sync/commit/aea6128ca5ae7e21f7ba687ead3f56326cce1b76))

## [1.1.8](https://github.com/AndreasAugustin/actions-template-sync/compare/v1.1.7...v1.1.8) (2023-09-24)


### Bug Fixes

* **ci:** :bug: issues within ci ([2793a56](https://github.com/AndreasAugustin/actions-template-sync/commit/2793a56cecdd0000c25e0a81972d78a45fbb4d97))

## [1.1.7](https://github.com/AndreasAugustin/actions-template-sync/compare/v1.1.6...v1.1.7) (2023-09-24)


### Bug Fixes

* **ci:** :bug:  ([#388](https://github.com/AndreasAugustin/actions-template-sync/issues/388)) issues within ci ([8649015](https://github.com/AndreasAugustin/actions-template-sync/commit/8649015f18ab9855f8d3b93c50d67444438bb14f))

## [1.1.6](https://github.com/AndreasAugustin/actions-template-sync/compare/v1.1.5...v1.1.6) (2023-09-24)


### Bug Fixes

* **ci:** :bug:  ([#388](https://github.com/AndreasAugustin/actions-template-sync/issues/388)) issues within ci ([dd57314](https://github.com/AndreasAugustin/actions-template-sync/commit/dd573140ec37a0e41ff179af7d9954a049c9eb93))

## [1.1.5](https://github.com/AndreasAugustin/actions-template-sync/compare/v1.1.4...v1.1.5) (2023-09-24)


### Bug Fixes

* **ci:** :bug:  ([#388](https://github.com/AndreasAugustin/actions-template-sync/issues/388)) issues within ci ([e063b29](https://github.com/AndreasAugustin/actions-template-sync/commit/e063b29c03ebb93b4185b752f4d8dc61db3605df))
* **ci:** :bug: ([#387](https://github.com/AndreasAugustin/actions-template-sync/issues/387)) issue with docker push ([#392](https://github.com/AndreasAugustin/actions-template-sync/issues/392)) ([a94785c](https://github.com/AndreasAugustin/actions-template-sync/commit/a94785c1d4150fac0168410757004e83f638caf1))

## [1.1.4](https://github.com/AndreasAugustin/actions-template-sync/compare/v1.1.3...v1.1.4) (2023-09-24)


### Bug Fixes

* **docs:** :bug: ([#387](https://github.com/AndreasAugustin/actions-template-sync/issues/387)) fix missing documentation about .templatesyncignore paths ([3130f5b](https://github.com/AndreasAugustin/actions-template-sync/commit/3130f5bc62a6f98ece2c209994283520fe3ca811))

## [1.1.3](https://github.com/AndreasAugustin/actions-template-sync/compare/v1.1.2...v1.1.3) (2023-09-16)


### Bug Fixes

* :bug: ([#380](https://github.com/AndreasAugustin/actions-template-sync/issues/380)) small fix related to remote file mode changes ([#383](https://github.com/AndreasAugustin/actions-template-sync/issues/383)) ([ff25f8c](https://github.com/AndreasAugustin/actions-template-sync/commit/ff25f8cbcd237716eeff23dc5616632c7663e99f))

## [1.1.2](https://github.com/AndreasAugustin/actions-template-sync/compare/v1.1.1...v1.1.2) (2023-09-03)


### Bug Fixes

* :bug: ([#375](https://github.com/AndreasAugustin/actions-template-sync/issues/375)) fix edge case with .templatesyncignore ([#378](https://github.com/AndreasAugustin/actions-template-sync/issues/378)) ([1eede30](https://github.com/AndreasAugustin/actions-template-sync/commit/1eede30772357d6984d1757753a672da4119d356))
