# Ember Data Changelog

## v4.6.1 (2022-07-28)

#### :bug: Bug Fix
* `-ember-data`, `adapter`, `canary-features`, `debug`, `model`, `private-build-infra`, `record-data`, `serializer`, `store`
  * [#8089](https://github.com/emberjs/data/pull/8089) fix: unpin yarn for consumers ([@runspired](https://github.com/runspired))

#### Committers: 1
- Chris Thoburn ([@runspired](https://github.com/runspired))

## v4.6.0 (2022-07-27)

4.6.0 is a re-release of 4.5.0. No new changes are involved.
## v4.5.0 (2022-07-27)

#### :rocket: Enhancement
* `-ember-data`, `private-build-infra`, `store`
  * [#7880](https://github.com/emberjs/data/pull/7880) [rfc]: deprecate RSVP.Promise ([@snewcomer](https://github.com/snewcomer))


#### :evergreen_tree: New Deprecation
* `-ember-data`, `adapter`, `model`, `private-build-infra`, `record-data`, `serializer`, `store`, `unpublished-model-encapsulation-test-app`
  * [#8055](https://github.com/emberjs/data/pull/8055) chore: Continuing InternalModel Burndown ([@runspired](https://github.com/runspired))

#### :bug: Bug Fix
* `-ember-data`, `adapter`
  * [#8083](https://github.com/emberjs/data/pull/8083) [BUGFIX] Serialize null array items as empty strings ([@camerondubas](https://github.com/camerondubas))
* `-ember-data`, `store`
  * [#7901](https://github.com/emberjs/data/pull/7901) fix: waiter should be always on ([@runspired](https://github.com/runspired))
* `-ember-data`, `adapter`, `canary-features`, `debug`, `model`, `private-build-infra`, `record-data`, `serializer`, `store`, `unpublished-adapter-encapsulation-test-app`, `unpublished-debug-encapsulation-test-app`, `unpublished-fastboot-test-app`, `unpublished-model-encapsulation-test-app`, `unpublished-record-data-encapsulation-test-app`, `unpublished-relationship-performance-test-app`, `unpublished-serializer-encapsulation-test-app`, `unpublished-test-infra`
  * [#8042](https://github.com/emberjs/data/pull/8042) fix: RecordState cleanup, drop requireESM and node12 ([@runspired](https://github.com/runspired))
* `-ember-data`, `debug`
  * [#8008](https://github.com/emberjs/data/pull/8008) schedule watchTypeIfUnseen to prevent loop ([@patricklx](https://github.com/patricklx))
* `adapter`, `model`, `private-build-infra`, `serializer`
  * [#8013](https://github.com/emberjs/data/pull/8013) [BUGFIX release] Fix generated import paths for test setup functions in addons ([@bertdeblock](https://github.com/bertdeblock))
* `-ember-data`, `model`, `store`
  * [#8025](https://github.com/emberjs/data/pull/8025) Fix: PromiseProxy Deprecation for Save ([@runspired](https://github.com/runspired))
* `-ember-data`
  * [#7902](https://github.com/emberjs/data/pull/7902) test for async hasMany does not trigger relationship fetch ([@snewcomer](https://github.com/snewcomer))
* `serializer`
  * [#7854](https://github.com/emberjs/data/pull/7854) fix: pass correct args to keyFor<Attribute|Relationship> when normalizing ([@runspired](https://github.com/runspired))
* `-ember-data`, `model`
  * [#7945](https://github.com/emberjs/data/pull/7945) fix for #7904 computed chains not updated for async hasMany loading ([@runspired](https://github.com/runspired))

#### :memo: Documentation
* `-ember-data`, `adapter`, `model`, `private-build-infra`, `record-data`, `serializer`, `store`, `unpublished-model-encapsulation-test-app`
  * [#8055](https://github.com/emberjs/data/pull/8055) chore: Continuing InternalModel Burndown ([@runspired](https://github.com/runspired))
* `model`
  * [#8002](https://github.com/emberjs/data/pull/8002) Update imports in doc code samples ([@CuriousCorrelation](https://github.com/CuriousCorrelation))
* [#7984](https://github.com/emberjs/data/pull/7984) Add `LICENSE.md` ([@ddzz](https://github.com/ddzz))

#### :shower: Deprecation Removal
* `-ember-data`, `adapter`, `debug`, `model`, `private-build-infra`, `record-data`, `store`, `unpublished-test-infra`
  * [#8078](https://github.com/emberjs/data/pull/8078) chore: InternalModel burndown ([@runspired](https://github.com/runspired))
* `-ember-data`, `model`, `record-data`, `store`, `unpublished-test-infra`
  * [#7971](https://github.com/emberjs/data/pull/7971) chore: remove the state machine ([@runspired](https://github.com/runspired))
* `-ember-data`, `adapter`, `debug`, `model`, `record-data`, `serializer`, `store`, `unpublished-adapter-encapsulation-test-app`, `unpublished-debug-encapsulation-test-app`, `unpublished-fastboot-test-app`, `unpublished-model-encapsulation-test-app`, `unpublished-record-data-encapsulation-test-app`, `unpublished-relationship-performance-test-app`, `unpublished-serializer-encapsulation-test-app`, `unpublished-test-infra`
  * [#7970](https://github.com/emberjs/data/pull/7970) chore: remove unused evented infra ([@runspired](https://github.com/runspired))
* `-ember-data`, `adapter`, `model`, `store`
  * [#7953](https://github.com/emberjs/data/pull/7953) chore: cleanup a few more leaf types ([@runspired](https://github.com/runspired))
* `-ember-data`
  * [#7623](https://github.com/emberjs/data/pull/7623) [CHORE]: Modernize Find-Test ([@runnerboy22](https://github.com/runnerboy22))
  * [#7952](https://github.com/emberjs/data/pull/7952) chore: migrate files that only re-export to ts to preserve type flow ([@runspired](https://github.com/runspired))
  * [#7951](https://github.com/emberjs/data/pull/7951) chore: remove unneeded version code in ember-data package ([@runspired](https://github.com/runspired))
  * [#7629](https://github.com/emberjs/data/pull/7629) [CHORE]: Modernize queries-test ([@runnerboy22](https://github.com/runnerboy22))
  * [#7624](https://github.com/emberjs/data/pull/7624) [CHORE]: Modernize find-all-test ([@runnerboy22](https://github.com/runnerboy22))
* `-ember-data`, `adapter`, `model`, `record-data`, `serializer`, `store`, `unpublished-adapter-encapsulation-test-app`, `unpublished-debug-encapsulation-test-app`, `unpublished-fastboot-test-app`, `unpublished-model-encapsulation-test-app`, `unpublished-record-data-encapsulation-test-app`, `unpublished-relationship-performance-test-app`, `unpublished-serializer-encapsulation-test-app`, `unpublished-test-infra`
  * [#7950](https://github.com/emberjs/data/pull/7950) some small cleanups and fix test container ([@runspired](https://github.com/runspired))
* `-ember-data`, `store`
  * [#7849](https://github.com/emberjs/data/pull/7849) Remove some usage of runtime require ([@SergeAstapov](https://github.com/SergeAstapov))

#### :goal_net: Test
* `-ember-data`, `adapter`, `canary-features`, `debug`, `model`, `private-build-infra`, `record-data`, `serializer`, `store`, `unpublished-adapter-encapsulation-test-app`, `unpublished-debug-encapsulation-test-app`, `unpublished-eslint-rules`, `unpublished-fastboot-test-app`, `unpublished-model-encapsulation-test-app`, `unpublished-record-data-encapsulation-test-app`, `unpublished-relationship-performance-test-app`, `unpublished-serializer-encapsulation-test-app`, `unpublished-test-infra`
  * [#8027](https://github.com/emberjs/data/pull/8027) fix test runs, update lts support tests ([@runspired](https://github.com/runspired))
* `-ember-data`
  * [#7628](https://github.com/emberjs/data/pull/7628) [CHORE]: Modernize json-api-adapter-test ([@runnerboy22](https://github.com/runnerboy22))
  * [#7626](https://github.com/emberjs/data/pull/7626) [CHORE]: Modernize build-url-mixin-strict-equal ([@runnerboy22](https://github.com/runnerboy22))
  * [#7630](https://github.com/emberjs/data/pull/7630) [CHORE]: Modernize record-persistence-test ([@runnerboy22](https://github.com/runnerboy22))
  * [#7625](https://github.com/emberjs/data/pull/7625) [CHORE]: Modernize client-side-delete-test ([@runnerboy22](https://github.com/runnerboy22))

#### :house: Internal
* `-ember-data`, `adapter`, `debug`, `model`, `private-build-infra`, `record-data`, `store`, `unpublished-test-infra`
  * [#8078](https://github.com/emberjs/data/pull/8078) chore: InternalModel burndown ([@runspired](https://github.com/runspired))
* `-ember-data`, `adapter`, `model`, `private-build-infra`, `record-data`, `serializer`, `store`, `unpublished-model-encapsulation-test-app`
  * [#8055](https://github.com/emberjs/data/pull/8055) chore: Continuing InternalModel Burndown ([@runspired](https://github.com/runspired))
* Other
  * [#8073](https://github.com/emberjs/data/pull/8073) [DOC] update pull request template ([@jenweber](https://github.com/jenweber))
* Other
  * [#7982](https://github.com/emberjs/data/pull/7982) Add GitHub Actions to Dependabot and update actions ([@ddzz](https://github.com/ddzz))
  * [#8026](https://github.com/emberjs/data/pull/8026) Deactivate Perf Benchmarks until Fixed ([@runspired](https://github.com/runspired))
* `-ember-data`, `adapter`, `canary-features`, `debug`, `model`, `private-build-infra`, `record-data`, `serializer`, `store`, `unpublished-adapter-encapsulation-test-app`, `unpublished-debug-encapsulation-test-app`, `unpublished-eslint-rules`, `unpublished-fastboot-test-app`, `unpublished-model-encapsulation-test-app`, `unpublished-record-data-encapsulation-test-app`, `unpublished-relationship-performance-test-app`, `unpublished-serializer-encapsulation-test-app`, `unpublished-test-infra`
  * [#8027](https://github.com/emberjs/data/pull/8027) fix test runs, update lts support tests ([@runspired](https://github.com/runspired))
* `-ember-data`, `adapter`, `model`, `private-build-infra`, `record-data`, `store`
  * [#7954](https://github.com/emberjs/data/pull/7954) port more types work over from #7585 ([@runspired](https://github.com/runspired))
* `-ember-data`
  * [#7622](https://github.com/emberjs/data/pull/7622) [CHORE]: Modernize Handle-Response-Test ([@runnerboy22](https://github.com/runnerboy22))
  * [#7631](https://github.com/emberjs/data/pull/7631) [CHORE]: Modernized serialize-test ([@runnerboy22](https://github.com/runnerboy22))
  * [#7624](https://github.com/emberjs/data/pull/7624) [CHORE]: Modernize find-all-test ([@runnerboy22](https://github.com/runnerboy22))

#### Committers: 10
- Chris Thoburn ([@runspired](https://github.com/runspired))
- Sergey Astapov ([@SergeAstapov](https://github.com/SergeAstapov))
- Tyler ([@runnerboy22](https://github.com/runnerboy22))
- Scott Newcomer ([@snewcomer](https://github.com/snewcomer))
- Darius Dzien ([@ddzz](https://github.com/ddzz))
- [@CuriousCorrelation](https://github.com/CuriousCorrelation)
- Bert De Block ([@bertdeblock](https://github.com/bertdeblock))
- [@patricklx](https://github.com/patricklx)
- Cameron Dubas ([@camerondubas](https://github.com/camerondubas))
- Jen Weber ([@jenweber](https://github.com/jenweber))

## v4.1.0 (2021-12-30)

#### :house: Internal
* [#7831](https://github.com/emberjs/data/pull/7831) Regen yarn lockfile ([@snewcomer](https://github.com/snewcomer))
* [#7830](https://github.com/emberjs/data/pull/7830) CHANGELOG 4.1.0 ([@snewcomer](https://github.com/snewcomer))

#### Committers: 1
- Scott Newcomer ([@snewcomer](https://github.com/snewcomer))


## v4.0.2 (2021-12-15)

#### :bug: Bug Fix
* `-ember-data`, `model`, `record-data`, `store`
  * [#7804](https://github.com/emberjs/data/pull/7804) Backport Train for Release ([@runspired](https://github.com/runspired))
* Other
  * [#7794](https://github.com/emberjs/data/pull/7794) [bug]: findRecord should not cache if includes differ (#7702) ([@snewcomer](https://github.com/snewcomer))

#### Committers: 2
- Chris Thoburn ([@runspired](https://github.com/runspired))
- Scott Newcomer ([@snewcomer](https://github.com/snewcomer))


## v4.0.0 (2021-12-11)

#### :shower: Deprecation Removal
* `-ember-data`, `adapter`, `debug`, `model`, `private-build-infra`, `record-data`, `serializer`, `store`, `unpublished-adapter-encapsulation-test-app`, `unpublished-debug-encapsulation-test-app`, `unpublished-fastboot-test-app`, `unpublished-model-encapsulation-test-app`, `unpublished-record-data-encapsulation-test-app`, `unpublished-serializer-encapsulation-test-app`, `unpublished-test-infra`
  * [#7767](https://github.com/emberjs/data/pull/7767) Remove TARGET_IE11 flag ([@snewcomer](https://github.com/snewcomer))
* `-ember-data`
  * [#7703](https://github.com/emberjs/data/pull/7703) fix tests ([@snewcomer](https://github.com/snewcomer))
* Other
  * [#7729](https://github.com/emberjs/data/pull/7729) Cache dependencies in GitHub Actions CI workflow ([@ddzz](https://github.com/ddzz))
  * [#7737](https://github.com/emberjs/data/pull/7737) Remove IE11 asset size checks ([@snewcomer](https://github.com/snewcomer))
* `-ember-data`, `private-build-infra`, `record-data`, `store`
  * [#7741](https://github.com/emberjs/data/pull/7741) Remove IE11 hacks ([@snewcomer](https://github.com/snewcomer))
* `adapter`, `store`, `unpublished-test-infra`
  * [#7740](https://github.com/emberjs/data/pull/7740) Remove symbol util in place of built in Symbol ([@snewcomer](https://github.com/snewcomer))
* `-ember-data`, `adapter`, `debug`, `model`, `record-data`, `serializer`, `store`, `unpublished-adapter-encapsulation-test-app`, `unpublished-debug-encapsulation-test-app`, `unpublished-fastboot-test-app`, `unpublished-model-encapsulation-test-app`, `unpublished-record-data-encapsulation-test-app`, `unpublished-serializer-encapsulation-test-app`, `unpublished-test-infra`
  * [#7739](https://github.com/emberjs/data/pull/7739) Remove TARGET_IE11 flag ([@snewcomer](https://github.com/snewcomer))

#### :evergreen_tree: New Deprecation
* `-ember-data`, `adapter`, `debug`, `model`, `private-build-infra`, `record-data`, `serializer`, `store`, `unpublished-adapter-encapsulation-test-app`, `unpublished-debug-encapsulation-test-app`, `unpublished-fastboot-test-app`, `unpublished-model-encapsulation-test-app`, `unpublished-record-data-encapsulation-test-app`, `unpublished-serializer-encapsulation-test-app`, `unpublished-test-infra`
  * [#7767](https://github.com/emberjs/data/pull/7767) Remove TARGET_IE11 flag ([@snewcomer](https://github.com/snewcomer))

#### :house: Internal
* [#7760](https://github.com/emberjs/data/pull/7760) chore: cancel older CI jobs ([@runspired](https://github.com/runspired))

#### Committers: 4
- Chris Thoburn ([@runspired](https://github.com/runspired))
- Darius D. ([@ddzz](https://github.com/ddzz))
- Igor Terzic ([@igorT](https://github.com/igorT))
- Scott Newcomer ([@snewcomer](https://github.com/snewcomer))

## v3.28.7 (2022-01-01)

#### :house: Internal
* [#7833](https://github.com/emberjs/data/pull/7833) CHANGELOG 3.28.7 ([@snewcomer](https://github.com/snewcomer))

#### Committers: 1
- Scott Newcomer ([@snewcomer](https://github.com/snewcomer))


## v3.28.4 (2021-11-23)

#### :bug: Bug Fix
* `-ember-data`, `private-build-infra`
  * [#7762](https://github.com/emberjs/data/pull/7762) chore(deps): bump broccoli-rollup from 4.1.1 to 5.0.0 (#7559) ([@snewcomer](https://github.com/snewcomer))

#### Committers: 1
- Scott Newcomer ([@snewcomer](https://github.com/snewcomer))


## v3.28.3 (2021-09-05)

#### :bug: Bug Fix
* `-ember-data`, `adapter`, `debug`, `model`, `serializer`, `store`
  * [#7698](https://github.com/emberjs/data/pull/7698) [BACKPORT Release] @ember/string to the latest version. The prior (#7697) ([@igorT](https://github.com/igorT))

#### Committers: 1
- Igor Terzic ([@igorT](https://github.com/igorT))


## v3.28.2 (2021-09-02)

#### :bug: Bug Fix
* `private-build-infra`
  * [#7694](https://github.com/emberjs/data/pull/7694) [Bugfix] ensure `shouldCompileModules` is once again respected (#7680) ([@igorT](https://github.com/igorT))

#### Committers: 1
- Igor Terzic ([@igorT](https://github.com/igorT))

## Release 3.28.0 (Aug 20, 2021)

#### :bug: Bug Fix

#### :rocket: Enhancement

- [#7258](https://github.com/emberjs/data/pull/7258) feat: record.destroyRecord should also unload the record ([@snewcomer](https://github.com/snewcomer))
- [#7510](https://github.com/emberjs/data/pull/7510) feat: activate all feature flags related to CUSTOM_MODEL_CLASSES ([@runspired](https://github.com/runspired))

#### :zap: Performance

- [#7505](https://github.com/emberjs/data/pull/7505) Perf: Refactor PromiseManyArray and prep for RFC#745 ([@runspired](https://github.com/runspired))
- [#7516](https://github.com/emberjs/data/pull/7516) Perf: eliminate retainedManyArrayCache ([@runspired](https://github.com/runspired))
- [#7454](https://github.com/emberjs/data/pull/7454) [PERF] Class Fields Use Optimization & Made OrderedSet Faster (Again) (#7454)
- [#7491](https://github.com/emberjs/data/pull/7491) relationship refactor part-1 (#7491)
- [#7493](https://github.com/emberjs/data/pull/7493) Relationship Refactor (part 2): The graph should coordinate state updates (#7493)

#### :bug: Bug Fix

- [#7651](https://github.com/emberjs/data/pull/7651) Return inflight requests for findRecord when CUSTOM_MODEL_CLASS is on (#7651) ([@igorT](https://github.com/igorT))
- [#7652](https://github.com/emberjs/data/pull/7652) Fix for CUSTOM_MODEL_CLASS and deprecate passing non ember data records to unloadRecord and deleteRecord (#7652) ([@igorT](https://github.com/igorT))
- [#7643](https://github.com/emberjs/data/pull/7643) @ember-data/model: Simplify @cached transpilation (#7599) ([@igorT](https://github.com/igorT))
- [#7554](https://github.com/emberjs/data/pull/7554) [BUGFIX] reset previously failed linked async belongs-to now works ([@sly7-7](https://github.com/sly7-7))
- [#7532](https://github.com/emberjs/data/pull/7532) fix: belongsTo should not attempt load if inverse in payload provided its data (#7049) ([@sly7-7](https://github.com/sly7-7))
- [#7550](https://github.com/emberjs/data/pull/7550) fix: add asserts and assert tests for belongsTo/hasMany/findRecord empty responses ([@runspired](https://github.com/runspired))
- [#7534](https://github.com/emberjs/data/pull/7534) fix: #7039 Ensure meta and links update when fetched relationship is empty or does not include the data key ([@sly7-7](https://github.com/sly7-7))
- [#7545](https://github.com/emberjs/data/pull/7545) [BUGFIX Model] assert when 'content' is used as a property on a record ([@zinyando](https://github.com/zinyando))
- [#7531](https://github.com/emberjs/data/pull/7531) fix: Closes [#7053](https://github.com/emberjs/data/issues/7053) issue preventing debug adapter removal from prod builds using the ember-data package ([@sly7-7](https://github.com/sly7-7))
- [#7527](https://github.com/emberjs/data/pull/7527) [BUGFIX] rollup step should deactivate ember modules polyfill >= 3.27 ([@runspired](https://github.com/runspired))
- [#7425](https://github.com/emberjs/data/pull/7425) Pass lid from relationship data to get record data (#7425)
- [#7448](https://github.com/emberjs/data/pull/7448) Bugfix: coalesceFindRequests should work with non native Adapter classes (#7448)
- [#7463](https://github.com/emberjs/data/pull/7463) chore: cleanup Implicit relationships (#7463)
- [#7453](https://github.com/emberjs/data/pull/7453) [CHORE] burndown of InternalModel methods that can be eliminated safely (#7453)
- [#7226](https://github.com/emberjs/data/pull/7226) refactor: Native Model (#7226)
- [#7470](https://github.com/emberjs/data/pull/7470) chore: convert relationships to use identifiers (#7470)

#### :memo: Documentation

- [#7549](https://github.com/emberjs/data/pull/7549) [DOC] Fixes JSONAPISerializer serialize documentation ([@skaterdav85](https://github.com/skaterdav85))
- [#7535](https://github.com/emberjs/data/pull/7535) fix adapter doc example ([@sly7-7](https://github.com/sly7-7))
- [#7447](https://github.com/emberjs/data/pull/7447) Document adapterOptions on REST adapter (#7447)


#### Committers: 9

- Chris Thoburn ([@runspired](https://github.com/runspired))
- Daniel Múnera Sánchez ([@dmuneras](https://github.com/dmuneras))
- David Tang ([@skaterdav85](https://github.com/skaterdav85))
- Lennex Zinyando ([@zinyando](https://github.com/zinyando))
- Sylvain MINA ([@sly7-7](https://github.com/sly7-7))
- Tyler ([@runnerboy22](https://github.com/runnerboy22))
- Scott Newcomer ([@snewcomer](https://github.com/snewcomer))
- Steven Pham ([@spham92](https://github.com/spham92))
- Igor Terzic ([@igorT](https://github.com/igorT))

## Release 3.27.1 (May 27, 2021)

- [#7552](https://github.com/emberjs/data/pull/7552) [BUGFIX release] rollup step should deactivate ember modules polyfill >= 3.27 (#7552)

## Release 3.27.0 (May 8, 2021)

- [#7435](https://github.com/emberjs/data/pull/7435) [Test]: fix for DataWrapper refactor in emberjs (#7435)

## Release 3.26.0 (March 26, 2021)

- [#7435](https://github.com/emberjs/data/pull/7435) [Test]: fix for DataWrapper refactor in emberjs (#7435)
- [#7416](https://github.com/emberjs/data/pull/7416) [Deps]: bump ember packages (#7416)
- [#7358](https://github.com/emberjs/data/pull/7358) [Chore]: TypeScript adapters (#7358)

## Release 3.25.0 (February 11, 2021)

- [#7394](https://github.com/emberjs/data/pull/7394) [Cleanup]: Remove RECORD_ARRAY_MANAGER_IDENTIFIERS (#7394)
- [#7393](https://github.com/emberjs/data/pull/7393) [Cleanup]: Remove FULL_LINKS_ON_RELATIONSHIPS (#7393)
- [#7292](https://github.com/emberjs/data/pull/7292) [DOC model] convert api examples to native classes/Octane (#7292)
- [#7399](https://github.com/emberjs/data/pull/7399) Fix deprecation URLs (#7399)
- [#7405](https://github.com/emberjs/data/pull/7405) [DOC adapter] fix parent class invocation syntax (#7405)

## Release 3.24.0 (January 4, 2021)

- [#7350](https://github.com/emberjs/data/pull/7350) [Chore]: convert adapters to class syntax
- [#7359](https://github.com/emberjs/data/pull/7359) [CI]: bump failure asset size to 75 bytes
- [#7369](https://github.com/emberjs/data/pull/7369) [CHORE] Bump @ember/ordered-set
- [#7370](https://github.com/emberjs/data/pull/7370) Don't expose the value of a model's attribute in assertions (#7370)
- [#7363](https://github.com/emberjs/data/pull/7363) [BUGFIX identifiers] Address issue with polymorphic findRecord

## Release 3.23.0 (November 30, 2020)

- [#7337](https://github.com/emberjs/data/pull/7337) [Debug]: improved debug msg instead of [object Object]
- [#7230](https://github.com/emberjs/data/pull/7230) [CHORE] najax deprecation when ember-fetch is also installed
- [#7370](https://github.com/emberjs/data/pull/7370) Don't expose the value of a model's attribute in assertions (#7370)
- [#7363](https://github.com/emberjs/data/pull/7363) [BUGFIX identifiers] Address issue with polymorphic findRecord (#7363)
- [#7338](https://github.com/emberjs/data/pull/7338) [Chore]: remove deprecation for DEPRECATE_MODEL_DATA
- [#7262](https://github.com/emberjs/data/pull/7262) [CHORE]: Extract internalModel access to identifiers for Relationships

## Release 3.22.0 (October 09, 2020)

- [#7126](https://github.com/emberjs/data/pull/7126) Bugfix for wrong hasMany relationship state in scenario of sideposting with lid
- [#7230](https://github.com/emberjs/data/pull/7230) [CHORE] najax deprecation when ember-fetch is also installed
- [#7330](https://github.com/emberjs/data/pull/7330) [BUG]: Consume array access to autotrack hasMany
- [#7273](https://github.com/emberjs/data/pull/7273) [BUGFIX] Entangle Errors.errorsFor properly
- [#7335](https://github.com/emberjs/data/pull/7335) [Bug]: errors `remove` to accurately update in template
- [#7322](https://github.com/emberjs/data/pull/7322) [Build]: disable esm cache (#7322)
- [#7263](https://github.com/emberjs/data/pull/7263) [CHORE]: Move symbols out of /ts-interfaces and into -private/utils
- [#6715](https://github.com/emberjs/data/pull/6715) [CHORE]: Extract internalModel access to identifiers in RecordArray modules

## Release 3.21.0 (August 30, 2020)

- [#7224](https://github.com/emberjs/data/pull/7224) [DOCS] fix links on @ember-data/store package intro
- [#7228](https://github.com/emberjs/data/pull/7228) chore: remove instance initializer (#7228)
- [#7232](https://github.com/emberjs/data/pull/7232) [DOC] Fix minor typo in findRecord documentation
- [#7231](https://github.com/emberjs/data/pull/7231) [DOC] Use native syntax in RESTSerializer documentation (#7231)

## Release 3.20.2 (LTS) (August 30, 2020)

- Rerelease of 3.20.1

## Release 3.20.1 (August 29, 2020)

- [#7273](https://github.com/emberjs/data/pull/7273) [BUGFIX] Entangle Errors.errorsFor properly

## Release 3.20.0 (July 16, 2020)

- [#7167](https://github.com/emberjs/data/pull/7167) [FEATURE] JSONAPI Serializer asserts instead of warning when passed EmbeddedRecordsMixin, opt out with `isEmbeddedRecordsMixinCompatible: true`
- [#7198](https://github.com/emberjs/data/pull/7198) [DOC] Update documentation around behavior of attr (#7198)
- [#7200](https://github.com/emberjs/data/commit/7d7e38ebdcfebbf368d31f1ccd53066fcd5d48b3) [DOC] Use native syntax in JSONAPISerializer documentation (#7200)
- [#7096](https://github.com/emberjs/data/pull/7096) [PERFORMANCE] Optimize visiting the relating records
- [#7090](https://github.com/emberjs/data/pull/7090) [PERFORMANCE] Optimize the update of a has-many relationship
- [#7235](https://github.com/emberjs/data/pull/7235) [BUGFIX] Allow createRecord responses without a type

## Release 3.19.0 (June 5, 2020)

- [76768a2f](https://github.com/emberjs/data/commit/76768a2fe85aacc8a6ea6006f2a8295bb11618bf) [BUGFIX] dont use Ember.get on internals (#7103)
- [6404a2db](https://github.com/emberjs/data/commit/6404a2db5c7b6a286f2a10926e508f93ea3b8371) [DOC] fix import path in JSON serializer documentation (#7111)
- [#6889](https://github.com/emberjs/data/pull/6889) [DEPRECATION] deprecate intimate Reference.internalModel (#6889)
- [#7146](https://github.com/emberjs/data/pull/7146) [BUGFIX]: Fix errors while running yarn start (#7146)
- [#7198](https://github.com/emberjs/data/pull/7198) [DOC] Update documentation around behavior of attr (#7198)
- [82d6f586](https://github.com/emberjs/data/commit/82d6f5860b9ac8f8a1590d9f136417165533740a) [DOC] Use native syntax in JSONAPISerializer documentation (#7200)
- [#7182](https://github.com/emberjs/data/pull/7182) [BUGFIX] Cache identifers globally, not just per type

## Release 3.18.0 (April 28, 2020)

- [#6941](https://github.com/emberjs/data/pull/6941) [BUGFIX] fix jsonapi error handling when not using jquery (#6941)
- [#7020](https://github.com/emberjs/data/pull/7020) Ensure adapters and serializers are destroyed upon store destruction. (#7020)
- [#7030](https://github.com/emberjs/data/pull/7030) Revert "Disable known failure for 3.16.x"
- [#7038](https://github.com/emberjs/data/pull/7038) [DOC] fix minor typo in Model overview documentation
- [#7043](https://github.com/emberjs/data/pull/7043) [DOC] modernize TimeoutError example code
- [#6958](https://github.com/emberjs/data/pull/6958) [DOC] Update embedded-records-mixin.js
- [#7019](https://github.com/emberjs/data/pull/7019) [DOC] create a howto for testing pull requests
- [78e0b41d](https://github.com/emberjs/data/commit/78e0b41d8bc545a750925cfc57336904bb7d7b2c) [BUGFIX] Fix #7015 - calling changedAttributes for non instantiated relationships

## Release 3.17.1 (April 28, 2020)

- [#7144](https://github.com/emberjs/data/pull/7144) [BUGFIX] dont use Ember.get on internals (#7103)
- [#7144](https://github.com/emberjs/data/pull/7144) chore: update lts tests (#7133)
- [#7144](https://github.com/emberjs/data/pull/7144) clear relationships during delete (#7109)
- [#7144](https://github.com/emberjs/data/pull/7144) clear initialState after construction (#7110)
- [#7144](https://github.com/emberjs/data/pull/7144) fix creation recursion with ember-data-model-fragments (#7123)
- [#7144](https://github.com/emberjs/data/pull/7144) fix: blueprint tests for classic (#7132)

## Release 3.17.0 (March 10, 2020)

- [#7020](https://github.com/emberjs/data/pull/7020) Ensure adapters and serializers are destroyed upon store destruction. (#7020)
- [#6941](https://github.com/emberjs/data/pull/6941) [BUGFIX] fix jsonapi error handling when not using jquery (#6941)
- [c36d42ae](https://github.com/emberjs/data/commit/c36d42aef7218fe2a34ab7cde6321fb08d7c9cca) [BUGFIX] Fix #7015 - calling changedAttributes for non instantiated relationshipsjj
- [f7340c9b](https://github.com/emberjs/data/commit/f7340c9b5be1c0b58b0357581761ccafc91bf27a) [DOCS] MinimumAdapterInterface (#6643)
- [e1822f96](https://github.com/emberjs/data/commit/e1822f96de83fb0b991d621007e3b866e618261d) [DOCS] Fix link for API Documentation (#6950)
- [3e3677f6](https://github.com/emberjs/data/commit/3e3677f6cfb3c8715697b302aed522d07926287f) [BUGFIX] fix importing from @ember-data/store
- [#6944](https://github.com/emberjs/data/pull/6944) chore: refactor: Remove last usages of run in adapter find tests (#6944)
- [#6985](https://github.com/emberjs/data/pull/6985) [FIX] RecordData is not a constructor
- [d776f1ec](https://github.com/emberjs/data/commit/d776f1ece2db0d3ec869f627d4e518c24e3f252a) [BUGFIX] findRecord should not resolve without id in production builds (#6561)
- [#6968](https://github.com/emberjs/data/pull/6968) remove IDENTIFIERS off branches (#6968)
- [#6927](https://github.com/emberjs/data/pull/6927) [FIX] groupRecordsForFindMany should be optional (#6927)
- [#7006](https://github.com/emberjs/data/pull/7006) Make execa use compatible with volta

## Release 3.16.9 (LTS) (August 29, 2020)

- [d22499d0](https://github.com/emberjs/data/pull/7291) [BUGFIX] Entangle Errors.errorsFor properly

## Release 3.16.8 (LTS) (June 24, 2020)

- [#7236](https://github.com/emberjs/data/pull/7236) [BUGFIX] Allow createRecord responses without a type (#7236)

## Release 3.16.7 (LTS) (June 10, 2020)

- [#7220](https://github.com/emberjs/data/pull/7220) [BUGFIX] Update ember-cli-babel to prevent errors with newer TS syntax (#7220)

## Release 3.16.6 (LTS) (May 13, 2020)

- [#7182](https://github.com/emberjs/data/pull/7182) [BUGFIX] Cache identifiers regardless of type, fixes polymorphism issues (#7182)

## Release 3.16.5 (LTS) (April 28, 2020)

- [#7144](https://github.com/emberjs/data/pull/7144) [BUGFIX] dont use Ember.get on internals (#7103)
- [#7144](https://github.com/emberjs/data/pull/7144) chore: update lts tests (#7133)
- [#7144](https://github.com/emberjs/data/pull/7144) clear relationships during delete (#7109)
- [#7144](https://github.com/emberjs/data/pull/7144) clear initialState after construction (#7110)
- [#7144](https://github.com/emberjs/data/pull/7144) fix creation recursion with ember-data-model-fragments (#7123)
- [#7144](https://github.com/emberjs/data/pull/7144) fix: blueprint tests for classic (#7132)

## Release 3.16.4 (LTS) (March 10 2020)

- Rerelease of 3.16.3

## Release 3.16.3 (March 10 2020)

- [cef0ed5c](https://github.com/emberjs/data/commit/cef0ed5c73e35e14dd5c398f6126307922d51c95) [BUGFIX] Fix #7015 - calling changedAttributes for non instantiated relationships

## Release 3.16.2 (February 27 2020)

- [#7020](https://github.com/emberjs/data/pull/7020) Ensure adapters and serializers are destroyed upon store destruction. (#7020)
- [#6941](https://github.com/emberjs/data/pull/6941) [BUGFIX] fix jsonapi error handling when not using jquery (#6941)

## Release 3.16.1 (February 27 2020)

- Never published.

## Release 3.16.0 (January 24 2020)

- [c07cee0b](https://github.com/emberjs/data/commit/c07cee0ba58c46001b638405c43dd4ce5941f9a6) [BUGFIX RELEASE BETA CANARY] Better fastboot crypto error message (#6692)
- [#6683](https://github.com/emberjs/data/pull/6683) [BUGFIX RELEASE BETA CANARY] Fastboot issues (#6683)
- [919fb21f](https://github.com/emberjs/data/commit/919fb21fac63a8c961f6e6c775b9f67e1b5bcec4) [BREAKING BUGFIX] eliminate infrastructure for filter record arrays (#6702)
- [#6673](https://github.com/emberjs/data/pull/6673) [BUGFIX TEST] reloading tests for adapter encapsulation side quest - shouldReloadAll (#6673)
- [#6711](https://github.com/emberjs/data/pull/6711) [BUGFIX TEST] reloading tests for adapter encapsulation side quest - shouldBackgroundReloadAll (#6711)
- [#6713](https://github.com/emberjs/data/pull/6713) [CHORE] refactor: Remove runloop usage in integration/store-tests module deleteRecord (#6713)
- [3641f293](https://github.com/emberjs/data/commit/3641f293e75fa2f84897f8754a330f54a352508e) [BUGFIX TEST] reloading tests for adapter encapsulation side quest - shouldReloadRecord (#6714)
- [c9a8908e](https://github.com/emberjs/data/commit/c9a8908e930b95e471784d4890b1f31be87a3759) [BUGFIX TEST] reloading tests for adapter encapsulation side quest - shouldBackgroundReloadRecord (#6718)
- [#6574](https://github.com/emberjs/data/pull/6574) [CHORE] - Removes allInverseRecordsAreLoaded from has-many and belongs-to state classes (#6574)
- [#6599](https://github.com/emberjs/data/pull/6599) Using a config to include ember-data/debug in the build (#6599)
- [#6712](https://github.com/emberjs/data/pull/6712) [CHORE] refactor: Remove runloop usage in integration tests for store/ find All module (#6712)
- [#6734](https://github.com/emberjs/data/pull/6734) [CHORE] build speed improvements & docs path fix (#6734)
- [493b7b22](https://github.com/emberjs/data/commit/493b7b223ae1e87f42a0cd472164a2a31c1770aa) [BUGFIX] only allow feature flag alterations in canary (#6738)
- [e13247cd](https://github.com/emberjs/data/commit/e13247cd45f4197e65d1848372b942f539263c8b) [DOC] Fix typo (#6741)
- [#6742](https://github.com/emberjs/data/pull/6742) Strip FeatureFlagged code in non canary builds
- [#6737](https://github.com/emberjs/data/pull/6737) [CHORE] add package flag infra, strip flag infra (#6737)
- [4baa29f5](https://github.com/emberjs/data/commit/4baa29f5c10438258e71b24f2dec1cb3994e53c4) [BUGFIX] ensure MandatorySetter does not trigger for modelName
- [#6752](https://github.com/emberjs/data/pull/6752) [CHORE] feature flag reversal test (#6752)
- [#6767](https://github.com/emberjs/data/pull/6767) [BUGFIX] fix detect usage for native class polymorphism (#6767)
- [#6766](https://github.com/emberjs/data/pull/6766) [CHORE issue-template] capture nested package deps in cli output (#6766)
- [#6763](https://github.com/emberjs/data/pull/6763) [CHORE] rename Record to RecordInstance (#6763)
- [118a0470](https://github.com/emberjs/data/commit/118a0470207d88d01080a0f63aac7aa82617ec55) [BUGFIX] Set IDs on Record Data when mutating DS Model (#6775)
- [#6802](https://github.com/emberjs/data/pull/6802) [CHORE] Move \_modelForMixin to Model package (#6802)
- [#6797](https://github.com/emberjs/data/pull/6797) [BUGFIX TEST] relationships tests for adapter enapsulation side quest (#6797)
- [#6809](https://github.com/emberjs/data/pull/6809) [BUGFIX] cleanup rollup warnings (#6809)
- [#6808](https://github.com/emberjs/data/pull/6808) [FIX] improve tarball insertion (#6808)
- [#6816](https://github.com/emberjs/data/pull/6816) fixed serialize example (#6816)
- [#6820](https://github.com/emberjs/data/pull/6820) [CHORE] improve comment bot (#6820)
- [#6823](https://github.com/emberjs/data/pull/6823) [FIX] comment-bot, partner-tests: use yarn lock-file when we can (#6823)
- [#6824](https://github.com/emberjs/data/pull/6824) [TEST] generateIdForRecord tests for adapter encapsulation side quest (#6824)
- [#6822](https://github.com/emberjs/data/pull/6822) [CHORE] Move PromiseBelongsTo, PromiseManyArray and ManyArray to model package (#6822)
- [#6826](https://github.com/emberjs/data/pull/6826) [CHORE] AssetSize check for both modern and IE11 builds (#6826)
- [#6828](https://github.com/emberjs/data/pull/6828) [CHORE] Fix workflow and enable partner test debugging (#6828)
- [#6830](https://github.com/emberjs/data/pull/6830) [CHORE] IE11 Testing (#6830)
- [a0158dec](https://github.com/emberjs/data/commit/a0158dec4af4870205281d29c1992e7bd2759c0d) [BUGFIX] Octane: should not need to use get with model.id (#6829)
- [#6835](https://github.com/emberjs/data/pull/6835) [CHORE] Use model name instead of store in isPrimaryType (#6835)
- [#6831](https://github.com/emberjs/data/pull/6831) [BUGFIX TESTS] matrix tests for fastboot & ie11 w/jquery & fetch (#6831)
- [#6847](https://github.com/emberjs/data/pull/6847) [FIX CI] fetch full history for checks against master (#6847)
- [#6844](https://github.com/emberjs/data/pull/6844) [CHORE] Cron job to check for external deprecations (#6844)
- [#6857](https://github.com/emberjs/data/pull/6857) fix nightly.yml (#6857)
- [#6814](https://github.com/emberjs/data/pull/6814) [FEAT] Strip resolved Deprecations (#6814)
- [#6859](https://github.com/emberjs/data/pull/6859) [CHORE] document canary feature-flag infra
- [#6861](https://github.com/emberjs/data/pull/6861) [DOCS] fix inclusion of docs for deprecation and canary features (#6861)
- [#6792](https://github.com/emberjs/data/pull/6792) improve urlForFindAll example (#6792)
- [#6865](https://github.com/emberjs/data/pull/6865) Revert dependency updates requiring Node 10+. (#6865)
- [#6801](https://github.com/emberjs/data/pull/6801) [CHORE ts] type Snapshot (#6801)
- [#6839](https://github.com/emberjs/data/pull/6839) [DEPRECATION] deprecate belongsToReference.push accepting a model (#6839)
- [#6881](https://github.com/emberjs/data/pull/6881) [TEST] deprecation infra (#6881)
- [#6871](https://github.com/emberjs/data/pull/6871) [BUGFIX] ensure handleResponse always called in rest adapter (#6871)
- [972c8114](https://github.com/emberjs/data/commit/972c811431c9e31764f012b75045b8d63958b546) [BUGFIX] fix single-table poymorphic-type-switch
- [#6986](https://github.com/emberjs/data/pull/6986) [BUFGIX BETA] dont run canary model tests in beta
- [4cbafa1e](https://github.com/emberjs/data/commit/4cbafa1e8c7103f76882f6f23e6637af68017ecd) v3.17.0-alpha.1
- [#6968](https://github.com/emberjs/data/pull/6968) remove IDENTIFIERS off branches (#6968)
- [#6985](https://github.com/emberjs/data/pull/6985) [FIX] RecordData is not a constructor
- [#7001](https://github.com/emberjs/data/pull/7001) Disable known failure for 3.16.x
- [#7003](https://github.com/emberjs/data/pull/7003) beta backports
- [#7006](https://github.com/emberjs/data/pull/7006) Make execa use compatible with volta
- [#7008](https://github.com/emberjs/data/pull/7008) Bump ember-cli-typescript
- [#7009](https://github.com/emberjs/data/pull/7009) Make execa use compatible with volta

## Release 3.15.1 (January 24, 2020)

- [7bc74620](https://github.com/emberjs/data/commit/7bc74620aad159f37eb75eee07293c8b89216048) [BUGFIX] fix importing from @ember-data/store
- [#6985](https://github.com/emberjs/data/pull/6985) [FIX] RecordData is not a constructor
- [#7001](https://github.com/emberjs/data/pull/7001) Disable known failure for 3.16.x
- [#7002](https://github.com/emberjs/data/pull/7002) 3.15.x release backports

## Release 3.15.0 (December 18, 2019)

- [#6586](https://github.com/emberjs/data/pull/6586) [BUGFIX] relationship setup for link fetch should batch (#6586)
- [1d6ce0e4](https://github.com/emberjs/data/commit/1d6ce0e44518c2046e5e472f5e348bab17f34f31) [BUGFIX] fix single-table poymorphic-type-switch
- [#6449](https://github.com/emberjs/data/pull/6449) [FIX DOCS] Docs updates for Packages to fix missing docs and broken links (#6449)
- [110712d5](https://github.com/emberjs/data/commit/110712d5cb990b107197c937b2a319ec82a83af3) [BUGFIX] only allow feature flag alterations in canary
- [22f7af03](https://github.com/emberjs/data/commit/22f7af034acfce9cee6b081d7134e81f9c9d724c) [BUGFIX] only include version in ember-data output (#6528)
- [db6967f3](https://github.com/emberjs/data/commit/db6967f3f076589c52bf3811bb36f1f363b50237) [BUGFIX] Set IDs on Record Data when mutating DS Model (#6775) (#6780)
- [9492196d](https://github.com/emberjs/data/commit/9492196d6dc8b50fec337b8b40c07ed2923ebf06) [BUGFIX] ensure MandatorySetter does not trigger for modelName (#6747)
- [4c6422ae](https://github.com/emberjs/data/commit/4c6422aea25dcf9d50088bc739309b3e73086ed8) [BUGFIX] Better fastboot crypto error message (#6698)
- [8942ee6f](https://github.com/emberjs/data/commit/8942ee6fb733c9b9ea796b34a4313e2fddb17d76) [BUGFIX adapter]: Fix problem with headers precedence #6588 (#6650)
- [b8287383](https://github.com/emberjs/data/commit/b828738391c662cbc9596cc9b619ab9b6dd9ee3e) [DOC] Close code block in the description
- [e9d54628](https://github.com/emberjs/data/commit/e9d546286f9e47376fe8116fa87be81103dcee2f) [BUGFIX fetchOptions] fix fetchOptions to support POST body of all valid types (#6562)
- [#6646](https://github.com/emberjs/data/pull/6646) [CHORE] refactor: Remove runloop usage in destroy module of integration/store… (#6646)
- [#6525](https://github.com/emberjs/data/pull/6525) [CHORE] moving files into Debug package (#6525)
- [#6549](https://github.com/emberjs/data/pull/6549) [CHORE] Removing detect function (and dependence on model package) in @debug (#6549)
- [#6568](https://github.com/emberjs/data/pull/6568) [BUGFIX] Enable `store.createRecord` in FastBoot (#6568)
- [#6587](https://github.com/emberjs/data/pull/6587) [BUGFIX] AdapterError reexport (#6587)
- [#6610](https://github.com/emberjs/data/pull/6610) [BUGFIX] modelFor should return a stable ShimModelClass (#6610)
- [#6606](https://github.com/emberjs/data/pull/6606) [FEAT links] ensures full links object support for relationships (#6606)
- [#6626](https://github.com/emberjs/data/pull/6626) [CHORE] adds infra for testing calls to Ember warn|deprecate|assert (#6626)
- [#6676](https://github.com/emberjs/data/pull/6676) [CHORE] Improve output and fail test for Asset size Check (#6676)
- [#6767](https://github.com/emberjs/data/pull/6767) [BUGFIX] fix detect usage for native class polymorphism (#6767)
- [#6871](https://github.com/emberjs/data/pull/6871) [BUGFIX] ensure handleResponse always called in rest adapter (#6871)
- [ae0b9647](https://github.com/emberjs/data/commit/ae0b964797b5c01c3d511a88781317fb9c18cdc2) [BUGFIX] Octane: should not need to use get with model.id (#6829)
- [#6871](https://github.com/emberjs/data/pull/6366) [FEAT identifiers] turn on IDENTIFIERS feature (#6366)

## Release 3.14.1 (December 18, 2019)

- [c408dd1d](https://github.com/emberjs/data/commit/c408dd1da5de55aaca782cc7850f0bdd4183a161) [BUGFIX] Better fastboot crypto error message (#6699)
- [#6708](https://github.com/emberjs/data/pull/6708) [BUGFIX] Fix Fastboot issues (#6683) (#6708)
- [358c229a](https://github.com/emberjs/data/commit/358c229aaf2179a64ebe1610dcd5f1d430406cde) [BUGFIX] ensure MandatorySetter does not trigger for modelName (#6748)
- [e44f6523](https://github.com/emberjs/data/commit/e44f65232c34b7db1bf8d0d681ceb39f1651c937) [BUGFIX] Set IDs on Record Data when mutating DS Model (#6775) (#6779)
- [c2fe49ab](https://github.com/emberjs/data/commit/c2fe49ab89eddf97736f54fa0fc1c78d76dd2eec) [BUGFIX] only allow feature flag alterations in canary (#6738)
- [#6767](https://github.com/emberjs/data/pull/6767) [BUGFIX] fix detect usage for native class polymorphism (#6767)
- [c8995256](https://github.com/emberjs/data/commit/c89952563a9353a710bdb4d621fb9bf418ab37ff) [BUGFIX] Octane: should not need to use get with model.id (#6829)

## Release 3.14.0 (November 7, 2019)

- [#6522](https://github.com/emberjs/data/pull/6522) [FIX DOCS] Docs updates for Packages to fix missing docs and broken links (#6449) (#6522)
- [#6568](https://github.com/emberjs/data/pull/6568) [BUGFIX] Enable `store.createRecord` in FastBoot (#6568)
- [#6586](https://github.com/emberjs/data/pull/6586) [BUGFIX links] relationship setup for link fetch should batch (#6586)
- [3f428ca9](https://github.com/emberjs/data/commit/3f428ca9d38b63059aa7e5f4c5a4055e9c5ec770) [BUGFIX adapter]: Fix problem with headers precedence #6588 (#6650)
- [#6234](https://github.com/emberjs/data/pull/6234) [BUGFIX relationships] fix proxy isDestroying error (#6234)
- [#6312](https://github.com/emberjs/data/pull/6312) [CHORE] Add environment variable to opt-out of rolling up `-private` (#6312)
- [396ae0aa](https://github.com/emberjs/data/commit/396ae0aabe707247e4da05756d17873d727adbc2) [BUGFIX beta] Update edition detection logic.
- [bb23403b](https://github.com/emberjs/data/commit/bb23403b97107c3579b593c1c8f6272f9f29a253) [DOCS BETA RELEASE] Fix @ember-data/model package is blank (#6444)
- [e61ab503](https://github.com/emberjs/data/commit/e61ab5038bdeebebfa7bbe44ea8242d553327b08) [BUGFIX] ensure we publish all packages regardless of changes (#6429)
- [bc7a0eca](https://github.com/emberjs/data/commit/bc7a0eca2eb0f244476aad724482819dc7d8b0f9) [DOC debug-adapter]: Add comments for each method in debug-adapter (#6352)
- [d4c48d52](https://github.com/emberjs/data/commit/d4c48d52dac9af60d7e1f89af7e29885656a0d9e) [BUGFIX] Fix Model lifecycle event deprecations
- [aa05d928](https://github.com/emberjs/data/commit/aa05d928737a2832051c8ffd1882d44db399794c) [FEAT] Adds support for parenless attr, belongsTo, and hasMany (#6339)
- [5c6a30c9](https://github.com/emberjs/data/commit/5c6a30c9e25377d253858f459eb73853e4d0867e) [BUGFIX] Fix Rollup warning about unresolved dependency
- [#6316](https://github.com/emberjs/data/pull/6316) [BUGFIX] Fix Rollup warning about unresolved dependency (#6316)
- [#6341](https://github.com/emberjs/data/pull/6341) [BUGFIX]: set Content-Type for non GET requests only (#6341)
- [#6334](https://github.com/emberjs/data/pull/6334) [BUGFIX] usage of recordDataFor for client side create needs to be in correct cache (#6334)
- [#6358](https://github.com/emberjs/data/pull/6358) [CHORE blueprints] Update blueprints to use package imports (#6358)
- [#6349](https://github.com/emberjs/data/pull/6349) [BUGFIX inspector] Set group name to relationship.kind (#6349)
- [#6452](https://github.com/emberjs/data/pull/6452) [BUGFIX beta] Update edition detection logic.
- [#6395](https://github.com/emberjs/data/pull/6395) [BUGFIX] Fix Model lifecycle event deprecations
- [#6390](https://github.com/emberjs/data/pull/6390) [DEPRECATION] RFC-522 implementation to add deprecations (#6390)
- [#6371](https://github.com/emberjs/data/pull/6371) [BUGFIX] Don't use Typescript in /app (#6371)
- [#6420](https://github.com/emberjs/data/pull/6420) Improve RecordReference, BelongsToReference and HasManyReference docs (#6420)
- [#6397](https://github.com/emberjs/data/pull/6397) [DOC] Added URL to `queryRecord` deprecation warning (#6397)
- [#6396](https://github.com/emberjs/data/pull/6396) [DOC] Added documentation URL to evented deprecation warnings (#6396)
- [#6410](https://github.com/emberjs/data/pull/6410) Remove module-unification blueprints
- [#6430](https://github.com/emberjs/data/pull/6430) [BUGFIX] make fetch function JIT (#6430)
- [#6450](https://github.com/emberjs/data/pull/6450) [CHORE]: Eliminate default injections in favor of re-export (#6450)
- [#6486](https://github.com/emberjs/data/pull/6486) [DOC] Fix meta example in reference.ts (#6486)
- [1e7c5738](https://github.com/emberjs/data/commit/1e7c5738b2866da41c00de31711f07e156193afd) [DOC serializer] implements MinimumSerializerInterface (#6451)

## Release 3.13.1 (September 24, 2019)

- [0ff38fb1](https://github.com/emberjs/data/commit/0ff38fb1c0a8d75c7ad03f5dc8eaf8193d7f6e80) [DOC serializer] implements MinimumSerializerInterface (#6451) (#6499)

## Release 3.13.0 (September 20, 2019)

- [b29baa17](https://github.com/emberjs/data/commit/b29baa176f91b87ffc28a0c11c2fdd1c079e5ad9) [DOCS BETA RELEASE] Fix @ember-data/model package is blank (#6444) (#6445)
- [8320ff4c](https://github.com/emberjs/data/commit/8320ff4c51012631af3af2ff50aa0ca679402b3f) [BUGFIX BETA RELEASE] Fix missing @babel/plugin-transform-block-scoping dependency (#6432)
- [d7454364](https://github.com/emberjs/data/commit/d7454364e262743206d86a9b88607d03fe4ae46f) [BUGFIX BETA] ensure produced artifacts correctly lock with each other (#6309)
- [a029725f](https://github.com/emberjs/data/commit/a029725f7372bae73b8cfbda307c3d2569b45b07) [BUGFIX beta] Fix Rollup warning about unresolved dependency
- [69749b86](https://github.com/emberjs/data/commit/69749b86fe7d3effea974edf0b12fc4316e02ebf) [BUGFIX release beta canary] Fix Model lifecycle event deprecations
- [#6312](https://github.com/emberjs/data/pull/6312) [BETA] Add environment variable to opt-out of rolling up `-private` (#6312)
- [#6292](https://github.com/emberjs/data/pull/6292) chore: ensure \* deps are hoisted (#6292)
- [#6337](https://github.com/emberjs/data/pull/6337) [CHORE] fix test observers to match ember canary changes (#6337)
- [#6411](https://github.com/emberjs/data/pull/6411) [BUGFIX beta] Adds support for parenless attr, belongsTo, and hasMany (#6339)
- [#6434](https://github.com/emberjs/data/pull/6434) [BUGFIX BETA RELEASE] make fetch function JIT (#6430) (#6434)
- [#6436](https://github.com/emberjs/data/pull/6436) fix: Strip Symbol from production builds (#6389) (#6436)
- [#6452](https://github.com/emberjs/data/pull/6452) [BUGFIX beta] Update edition detection logic.
- [#6334](https://github.com/emberjs/data/pull/6334) [BUGFIX BETA CANARY] usage of recordDataFor for client side create needs to be in correct cache
- [#6430](https://github.com/emberjs/data/pull/6430) [BUGFIX BETA RELEASE] make fetch function JIT

## Release 3.12.6 (LTS) (March 9, 2020)

- [3032e94c](https://github.com/emberjs/data/commit/3032e94cea8c2c3d19e643dfc071e63357277d4b) [BUGFIX] only allow feature flag alterations in canary (#6738)
- [51b0572e](https://github.com/emberjs/data/commit/51b0572eb197e0757dea674fea478135e983e267) [BUGFIX] Fix headers precedence warning for null headers object
- [#7020](https://github.com/emberjs/data/pull/7020) Ensure adapters and serializers are destroyed upon store destruction. (#7020)
- [51b0572e](https://github.com/emberjs/data/commit/82cd91419b7c14c91fb10d9190b8534d7c84d4b4) [BUGFIX] Add @canary-features as -build-infra dep

## Release 3.12.5 (LTS) (November 21, 2019)

- [#6524](https://github.com/emberjs/data/pull/6524) [DOCS] Docs updates for Packages to fix missing docs and broken links (#6524)
- [b101be12](https://github.com/emberjs/data/commit/b101be12f6598b9f7ee9cbbcdff88762c074d3ee) [BUGFIX] ensure MandatorySetter does not trigger for modelName (#6749)
- [c5f85800](https://github.com/emberjs/data/commit/c5f858008ee6eb2e01a57cfdf21005eb00452066) [BUGFIX] Set IDs on Record Data when mutating DS Model (#6775) (#6778)
- [#6744](https://github.com/emberjs/data/pull/6744) [BUGFIX] ensure feature flagged code is stripped out

## Release 3.12.4 (LTS) (September 24, 2019)

- [e10c8cf8](https://github.com/emberjs/data/commit/e10c8cf848f28bf6ce3ff9a654138b04e4b4a2d2) [DOC serializer] implements MinimumSerializerInterface (#6451) (#6500)

## Release 3.12.3 (LTS) (September 20, 2019)

- [#6441](https://github.com/emberjs/data/pull/6441) [BUGFIX] Await potentially async operations (#6441)
- [0cef1775](https://github.com/emberjs/data/commit/0cef177588351f25eeb20ca1eb4235ca6bfd0c03) [DOCS BETA RELEASE] Fix @ember-data/model package is blank (#6444) (#6446)

## Release 3.12.2 (September 11, 2019)

- [#6435](https://github.com/emberjs/data/pull/6435) [BUGFIX BETA RELEASE] make fetch function JIT (#6430) (#6435)
- [d3a1123e](https://github.com/emberjs/data/commit/d3a1123e61fcd0acb40a1ed01c90e4ae9e0280a1) [BUGFIX BETA RELEASE] Fix missing @babel/plugin-transform-block-scoping dependency (#6432) (#6437)

## Release 3.12.1 (September 11, 2019)

- [#6416](https://github.com/emberjs/data/pull/6416) [BUGFIX 3.12] Backport Symbol fix (#6416)
- [#6422](https://github.com/emberjs/data/pull/6422) [BUGFIX] ensure commit based versioning passes semver (#6422)
- [6fa2e23d](https://github.com/emberjs/data/commit/6fa2e23d977fc616a5531d1575f24806f5494411) [BUGFIX] ensure we publish all packages regardless of changes
- [598993fe](https://github.com/emberjs/data/commit/598993fe26157abab7478745e683c584cc2c9ae4) [BUGFIX] ensure produced artifacts correctly lock with each other (#6309) (#6310)

## Release 3.12.0

- [#6062](https://github.com/emberjs/data/pull/6062) [BUGFIX fetch] prevent Accept & ContentType header overwriting (#6062)
- [82743675](https://github.com/emberjs/data/commit/8274367556e4f23b2b8f8ac49c91e3d410a1f7bb) [BUGFIX release] Fix rollup warnings for require as an external module. (#6095)
- [545285f1](https://github.com/emberjs/data/commit/545285f1ca519a282272ccae6dfeb1c480f2e015) [BUGFIX release] Fix rollup warning for ember-inflector. (#6242)
- [48dd8120](https://github.com/emberjs/data/commit/48dd812035f974c56447ddc0cf81c37a83ce1e02) [BUGFIX reload] fix sync belongsTo reload w/dematerialize (#6158)
- [#6124](https://github.com/emberjs/data/pull/6124) chore: remove co usage (#6124)
- [#6155](https://github.com/emberjs/data/pull/6155) Two small fixes to `fetch` (#6155)
- [#6153](https://github.com/emberjs/data/pull/6153) Fix yuidoc setup to support the split packages (#6153)
- [#6078](https://github.com/emberjs/data/pull/6078) Use HTML comments in PR template. (#6078)
- [#6077](https://github.com/emberjs/data/pull/6077) [BUGFIX release] Remove ember-fetch dependency. (#6077)
- [#6112](https://github.com/emberjs/data/pull/6112) [BUGFIX relationships] fix infinite retry bug for failed relationship fetches (#6112)
- [#6125](https://github.com/emberjs/data/pull/6125) [CHORE tests] replace `mocha-only-detector` with `mocha/no-exclusive-tests` rule (#6125)
- [#6079](https://github.com/emberjs/data/pull/6079) docs: fix RELEASE.md refs to publish.js
- [#6247](https://github.com/emberjs/data/pull/6247) [RFC 403] Identifiers Infra (#6247)
- [#6274](https://github.com/emberjs/data/pull/6274) [BUGFIX RELEASE] Fix generating from blueprints (#6274)
- [#6168](https://github.com/emberjs/data/pull/6168) [DOCS adapter] remove remaining sinceToken and update docs (#6168)
- [#6181](https://github.com/emberjs/data/pull/6181) Docs update for unloadRecord
- [#6241](https://github.com/emberjs/data/pull/6241) [BUGFIX release] Add blueprints to ember-data package.
- [#6196](https://github.com/emberjs/data/pull/6196) Docs: fixing request->record typo (#6196)
- [#6252](https://github.com/emberjs/data/pull/6252) [BUGFIX] Includes yuidoc's output data.json to published package
- [#6281](https://github.com/emberjs/data/pull/6281) [BUGFIX release] ensure all packages in correct RFC locations (#6281)
- [#6256](https://github.com/emberjs/data/pull/6256) [BUGFIX release] fix type overrides (#6256)
- [#6250](https://github.com/emberjs/data/pull/6250) [BUGFIX query] Remove arity check for adapter.query (#6250)
- [#6280](https://github.com/emberjs/data/pull/6280) [DOC release] Fix API doc issues with package split. (#6280)
- [#6249](https://github.com/emberjs/data/pull/6249) chore: refactor store to class (#6249)

## Release 3.11.4 (July 26, 2019)

- [#6286](https://github.com/emberjs/data/pull/6286) [BUGFIX RELEASE] Fix generating from blueprints (#6274) (#6286)

## Release 3.11.3 (July 25, 2019)

- [#6280](https://github.com/emberjs/data/pull/6280) [DOC release] Fix API doc issues with package split. (#6280)
- [#6281](https://github.com/emberjs/data/pull/6281) [BUGFIX release] ensure all packages in correct RFC locations (#6281)

## Release 3.11.2 (July 20, 2019)

- [#6252](https://github.com/emberjs/data/pull/6252) [BUGFIX] Includes yuidoc's output data.json to published package

## Release 3.11.1 (July 19, 2019)

- [#6256](https://github.com/emberjs/data/pull/6256) [BUGFIX release] fix type overrides (#6256)
- [62ac6580](https://github.com/emberjs/data/commit/62ac658048eafa779cf7f566f6b2c088fb6c6a4a) [BUGFIX docs] ensure we publish docs (#6257)
- [fa67c329](https://github.com/emberjs/data/commit/fa67c329f4a11c2ea16d374684239d1a89869cc6) [BUGFIX release] Add blueprints to ember-data package.

## Release 3.11.0 (June 28, 2019)

- [#6189](https://github.com/emberjs/data/pull/6189) Update model API docs to use the new packages import syntax (#6137)
- [#6075](https://github.com/emberjs/data/pull/6075) [BUGFIX fetch] prevent Accept & ContentType header overwriting (#6062)
- [6c2ae3d4](https://github.com/emberjs/data/commit/6c2ae3d4eaae5c090d9b4bda6e5afc8f15f73d70) [BUGFIX release] Fix rollup warnings for require as an external module. (#6095)
- [88b37e2b](https://github.com/emberjs/data/commit/88b37e2bfdf749987aeca96636a203216c3d7ebf) [BUGFIX unloadRecord] Fix unloadRecord() when unloading a previous parent of a child record
- [a4c47189](https://github.com/emberjs/data/commit/a4c471899c4c17dca2b7385e5c554506921db45f) [BUGFIX docs] Update 'navigator.connection' example to spec (#6060)
- [fc69c462](https://github.com/emberjs/data/commit/fc69c4629747d20e9faa132d11edd2e7bf2892a1) [BUGFIX docs] Fix broken ArrayProxy link on api docs (#6057)
- [00df008f](https://github.com/emberjs/data/commit/00df008f874c2719c1253c217ecd10243d5fdb21) [FEAT packages] introduce build-infra package
- [e4a4368d](https://github.com/emberjs/data/commit/e4a4368d2278179410553aa8b601cd72dd7f7db6) [FIX recordArrayManager] removes an extraneous flush
- [781aecff](https://github.com/emberjs/data/commit/781aecff9b63781be5331c5885d06ac1be143d61) [DOC contributing.md] | Clarifying that yarn should be used to run tests, not ember
- [d184441b](https://github.com/emberjs/data/commit/d184441bc4c6416f5c8539566bc5277f9270b764) [BUGFIX jQuery] avoid jQuery deprecation notice for intentional use
- [67bf0b0e](https://github.com/emberjs/data/commit/67bf0b0e29a4f38285c6d24507204e644dd0effc) [BUGFIX blueprints] Add parans to the attr decorator when there is no transform type (#6054)
- [#5974](https://github.com/emberjs/data/pull/5974) Remove Publish job from CI (#5974)
- [678f3c9d](https://github.com/emberjs/data/commit/678f3c9d3eb962a039e02f25da0c3ae3473edb11) [BUGFIX partner-tests] fix directory resolution (#6064)

## Release 3.10.0 (May 13, 2019)

Re-release of 3.9.3 to allow for an extended stabilization period for the [Packages RFC](https://github.com/emberjs/data/labels/TRACK-packages)

## Release 3.9.3 (May 9, 2019)

- [ab45d352](https://github.com/emberjs/data/commit/ab45d352cac06c8a5fd10e92cf99accc96a19ff7) [BUGFIX release] Fix fetch detection.
- [0dce363b](https://github.com/emberjs/data/commit/0dce363bb99118e8aae051a9660c78f9be880850) [BUGFIX release] Fix rollup warnings for require as an external module. (#6095)

## Release 3.9.2 (May 7, 2019)

- [#6076](https://github.com/emberjs/data/pull/6076) [BUGFIX fetch] prevent Accept & ContentType header overwriting (#6062)
- [#6082](https://github.com/emberjs/data/pull/6082) [BUGFIX release] Remove ember-fetch dependency. (#6082)

## Release 3.9.1 (April 19, 2019)

- [7e3ca651](https://github.com/emberjs/data/commit/7e3ca651e0ce2525cfab666870e54fd16d23b57c) [BUGFIX jQuery] avoid jQuery deprecation notice for intentional use
- [BUGFIX fastboot] ember-fetch fastboot passthrough

### Release 3.9.0 (April 8, 2019)

- [1ebff8cb](https://github.com/emberjs/data/commit/1ebff8cb4bcd848e797a056f8cab9a80405772d8) [DOCS][bugfix] Get model relationships by string
- [a095bebf](https://github.com/emberjs/data/commit/a095bebf1ac94a116dcfd1919fd454c962b0bb13) [DOCS][bugfix] Adding type to forEach app serializer
- [d13e7840](https://github.com/emberjs/data/commit/d13e7840e6dead927842f095c3c8f2a4537abf50) [DOC serializeHasMany ] Update ember-data imports
- [2858c32d](https://github.com/emberjs/data/commit/2858c32dbc9458bb28f95c31a5afdeb7a499ea35) [DOCS][bugfix] recordRef push param must be with type
- [328e1b4f](https://github.com/emberjs/data/commit/328e1b4ff81ac3beb5688bed60717b049f7aa671) [DOCS][bugfix] Added attributes wrapper object
- [4fdde1ed](https://github.com/emberjs/data/commit/4fdde1edb36372913f8e5271180e95cc5d47ccac) [BUGFIX #5918] Fix promise not being returned
- [1dbe1015](https://github.com/emberjs/data/commit/1dbe10158fc3b5e36bdf3fb202b744a82a8a1756) [DOCS][bugfix] generateIdForRecord api doc #5803
- [739f78e3](https://github.com/emberjs/data/commit/739f78e381762525b90bbf91c96578b2ca418e62) [BUGFIX canary] eliminate recordData prop restriction
- [a61651df](https://github.com/emberjs/data/commit/a61651df4b6c1e759cf308212b9272055cf4e9a9) [BUGFIX canary] Fix options assignment in json-api adapter
- [f26d07b6](https://github.com/emberjs/data/commit/f26d07b62e4240f723a822b73d5a196ebee8de22) [BUGFIX fetch] Don't set json:api content-type for DELETE requests
- [75c77a74](https://github.com/emberjs/data/commit/75c77a7427d397e49e835d00c9c7b7403ef99c26) [FIX transforms] don't instantiate via `new`
- [081432ce](https://github.com/emberjs/data/commit/081432cec3d3a11388046ffc7ea1dd661172ed27) [FIX ManyArray] Evented.off requires a reference to the original callback
- [1df83339](https://github.com/emberjs/data/commit/1df833396855d956b817540923dd89338463fec2) [BUGFIX model] assertions around create need to account for Ember's own

### Release 3.8.0 (February 20, 2019)

- [#5671](https://github.com/emberjs/data/pull/5671) Use \_scheduleFetch instead of \_fetchRecord for belongsTo relationship (#5671)
- [#5702](https://github.com/emberjs/data/pull/5702) [CHORE reference] update reference to be ES2015
- [#5763](https://github.com/emberjs/data/pull/5763) Update Release instructions
- [#5736](https://github.com/emberjs/data/pull/5736) [DOC] Add Reference doc and AdapterError uses
- [#5733](https://github.com/emberjs/data/pull/5733) [BUGFIX inspector] Fix columns names in debug-adapter (#5733)
- [#5735](https://github.com/emberjs/data/pull/5735) Clarify load/reload behavior
- [#5721](https://github.com/emberjs/data/pull/5721) [BUGFIX 5720] - assert that replacing has-many with non-array throws assertion
- [#5749](https://github.com/emberjs/data/pull/5749) [DOC beta] Fix broken links
- [#5743](https://github.com/emberjs/data/pull/5743) drop use of MODEL_FACTORY_FOR

### Release 3.7.0 (January 8, 2019)

- Re-release of 3.6.0

### Release 3.6.0 (December 12, 2018)

- [#5671](https://github.com/emberjs/data/pull/5671) Fix issue preventing coalescing of belongsTo
- [#5700](https://github.com/emberjs/data/pull/5700) [CHORE] remove deprecations targeted for 3.5 (#5700)
- [#5733](https://github.com/emberjs/data/pull/5733) [BUGFIX inspector] Fix columns names in debug-adapter (#5733)

### Release 3.5.2 (November 29, 2018)

- [#5766](https://github.com/emberjs/data/pull/5766) [BUGFIX] update ember-cli-babel to ensure @ember/canary-features is available
- [#5769](https://github.com/emberjs/data/pull/5769) [BUGFIX beta] backport #5767 Make \_recordData lazy

### Release 3.5.1 (November 28, 2018)

- [#5762](https://github.com/emberjs/data/pull/5762) [BUGFIX unloadRecord] bfs compatibility for custom RecordData (#5703)

### Release 3.5.0 (October 12, 2018)

- [#5491](https://github.com/emberjs/data/pull/5491) [Feature] Add MU support for model and model-test blueprints
- [#5616](https://github.com/emberjs/data/pull/5616) [FEAT RecordData] turn on the build-flag by default
- [#5608](https://github.com/emberjs/data/pull/5608) [BUGFIX] Add inverse relationship on payload when missing (#5608)
- [#5489](https://github.com/emberjs/data/pull/5489) [BUGFIX] Lowercase header names in parseResponseHeaders
- [#5494](https://github.com/emberjs/data/pull/5494) [Feature] Add MU support for serializer and serializer-test blueprints
- [#5495](https://github.com/emberjs/data/pull/5495) [Feature] Add MU transform{,-test} blueprints
- [#5657](https://github.com/emberjs/data/pull/5657) [BUGFIX blueprints] remove second string argument from transform tests
- [#5652](https://github.com/emberjs/data/pull/5652) [Docs] Update buildUrl syntax in docs
- [#5639](https://github.com/emberjs/data/pull/5639) Include request/response info with Abort error
- [#5646](https://github.com/emberjs/data/pull/5646) [CHORE] update contribution guidelines
- [#5623](https://github.com/emberjs/data/pull/5623) Added conditional check to extract polymorphic relationship for hasMany (#5623)
- [#5650](https://github.com/emberjs/data/pull/5650) [FEAT transforms] makes the assertion for missing transforms clearer
- [#5640](https://github.com/emberjs/data/pull/5640) [BUGFIX] fix deprecation for store entry methods
- [#5654](https://github.com/emberjs/data/pull/5654) add mocha rfc232 blueprints
- [#5665](https://github.com/emberjs/data/pull/5665) add remaining mocha rfc 232 blueprints (#5665)
- [#5667](https://github.com/emberjs/data/pull/5667) Added check to extract polymorphic relationship for hasMany (#5623)

### Release 3.4.1 (September 14, 2018)

- [#5621](https://github.com/emberjs/data/pull/5621) Add partner test for the ilios frontend
- [#5589](https://github.com/emberjs/data/pull/5589) fix broken link because the new API website does not support the anchor
- [#5582](https://github.com/emberjs/data/pull/5582) [BUGFIX] Reference.reload should not cause sync-relationship assertion (#5582)
- [#5584](https://github.com/emberjs/data/pull/5584) Additional test coverage for async belongsTo mutation (#5584)
- [#5592](https://github.com/emberjs/data/pull/5592) Grammar fixes
- [#5602](https://github.com/emberjs/data/pull/5602) Publish docs to npm (#5602)
- [#5620](https://github.com/emberjs/data/pull/5620) [DOC release] Change misleading documentation for AdapterPopulatedRecordArray
- [#5622](https://github.com/emberjs/data/pull/5622) remove deletes (#5622)
- [#5624](https://github.com/emberjs/data/pull/5624) [BUGFIX] fix promise labels
- [#5627](https://github.com/emberjs/data/pull/5627) [FEAT adapterOptions] Ensure adapterOptions use is possible throughout (#5627)
- [#5632](https://github.com/emberjs/data/pull/5632) cleanup code climate config

### Release 3.4.0 (August 27, 2018)

- [#5540](https://github.com/emberjs/data/pull/5540) revert is-empty flag change, leave todo (#5540)
- [#5545](https://github.com/emberjs/data/pull/5545) [FEAT] TrackableRequests for when async leakage is detected
- [#5551](https://github.com/emberjs/data/pull/5551) Fix `floating dependencies` test suite (#5551)
- [#5557](https://github.com/emberjs/data/pull/5557) Fixup transpilation issues with @ember/ordered-set. (#5557)
- [#5559](https://github.com/emberjs/data/pull/5559) Dependency roundup!
- [#5562](https://github.com/emberjs/data/pull/5562) [BUGFIX] use internalModel promise if already loading (#5562)
- [#5566](https://github.com/emberjs/data/pull/5566) Acceptance Tests for belongsTo
- [#5567](https://github.com/emberjs/data/pull/5567) [FEAT] enable external partner testing
- [#5549](https://github.com/emberjs/data/pull/5549) [BUGFIX beta] Replace Object.assign with Ember polyfill assign (#5549)
- [#5540](https://github.com/emberjs/data/pull/5540) revert is-empty flag change, leave todo (#5540)
- [#5544](https://github.com/emberjs/data/pull/5544) remove test waiter (#5544)
- [#5543](https://github.com/emberjs/data/pull/5543) Do not publish yarn.lock to npm
- [#5477](https://github.com/emberjs/data/pull/5477) [BUGFIX] normalize model name for belongs to relationships (#5477)
- [#5518](https://github.com/emberjs/data/pull/5518) [BUGFIX] Clarifying error message for polymorphic types (#5518)
- [#5520](https://github.com/emberjs/data/pull/5520) Add 2.18.3 release to the changelog on master
- [#5526](https://github.com/emberjs/data/pull/5526) Update links to builds page fixtures
- [#5528](https://github.com/emberjs/data/pull/5528) Add tests for createRecord+unloadRecord
- [#5531](https://github.com/emberjs/data/pull/5531) broccoli-babel-transpiler appears only used in tests, otherwise it uses
- [#5531](https://github.com/emberjs/data/pull/5531) broccoli-babel-transpiler appears only used in tests, otherwise it uses
- [#5533](https://github.com/emberjs/data/pull/5533) [BUGFIX] fix and tests for belongs-to proxy not properly updating (#5533)
- [#5536](https://github.com/emberjs/data/pull/5536) [BUGFIX beta] Upgrading ember-inflector to v3.3.0
- [#5467](https://github.com/emberjs/data/pull/5467) [BUGFIX] don't cause unnecessary work during destroy
- [#5411](https://github.com/emberjs/data/pull/5411) Remove deprecations scheduled for 3.0
- [#5117](https://github.com/emberjs/data/pull/5117) Give Model a static toString method
- [#5429](https://github.com/emberjs/data/pull/5429) improve tests for unloading relationships
- [#5469](https://github.com/emberjs/data/pull/5469) Revamp eslint configuration.
- [#5439](https://github.com/emberjs/data/pull/5439) [FEAT] FASTBOOT SHOEBOX - Use actions queue so rehydration works
- [#5432](https://github.com/emberjs/data/pull/5432) Remove exists-sync dependency
- [#5436](https://github.com/emberjs/data/pull/5436) [CHORE] remove all usage of Ember.copy
- [#5438](https://github.com/emberjs/data/pull/5438) [BUGFIX] ensure destroy-sync cleanup is correct
- [#5437](https://github.com/emberjs/data/pull/5437) [CHORE] removes deprecated Store.filter feature
- [#5462](https://github.com/emberjs/data/pull/5462) [BUGFIX] ensure ManyArray state is in-sync with relationship state
- [#5446](https://github.com/emberjs/data/pull/5446) [CLEANUP] fix model and factory lookup
- [#5466](https://github.com/emberjs/data/pull/5466) Serialize empty hasMany relationships
- [#5461](https://github.com/emberjs/data/pull/5461) [BUGFIX] update content of proxy for async belongs-to relationships when null data received
- [#5471](https://github.com/emberjs/data/pull/5471) [CHORE] cull unnecessary files left from previous build setups
- [#5476](https://github.com/emberjs/data/pull/5476) [Feature] added module-unification adapter and adapter-test blueprints
- [#5508](https://github.com/emberjs/data/pull/5508) [CHORE] Update Dependencies

### Release 3.3.1 (July 26, 2018)

- [#5541](https://github.com/emberjs/data/pull/5541) [BUGFIX] backport fix for belongsTo proxy update

### Release 3.2.1 (July 26, 2018)

- [#5541](https://github.com/emberjs/data/pull/5541) [BUGFIX] backport fix for belongsTo proxy update

### Release 2.18.4 (July 24, 2018)

- [#5376](https://github.com/emberjs/data/pull/5376) [bugfix beta] Fetch cancels unload

### Release 3.3.0 (July 13, 2018)

- Re-release of Ember Data 3.2.0

### Release 3.3.0-beta.1 (June 29, 2018)

- [#5467](https://github.com/emberjs/data/pull/5467) [BUGFIX] don't cause unnecessary work during destroy
- [#5411](https://github.com/emberjs/data/pull/5411) Remove deprecations scheduled for 3.0
- [#5117](https://github.com/emberjs/data/pull/5117) Give Model a static toString method
- [#5429](https://github.com/emberjs/data/pull/5429) improve tests for unloading relationships
- [#5469](https://github.com/emberjs/data/pull/5469) Revamp eslint configuration.
- [#5439](https://github.com/emberjs/data/pull/5439) [FEAT] FASTBOOT SHOEBOX - Use actions queue so rehydration works
- [#5432](https://github.com/emberjs/data/pull/5432) Remove exists-sync dependency
- [#5436](https://github.com/emberjs/data/pull/5436) [CHORE] remove all usage of Ember.copy
- [#5438](https://github.com/emberjs/data/pull/5438) [BUGFIX] ensure destroy-sync cleanup is correct
- [#5437](https://github.com/emberjs/data/pull/5437) [CHORE] removes deprecated Store.filter feature
- [#5462](https://github.com/emberjs/data/pull/5462) [BUGFIX] ensure ManyArray state is in-sync with relationship state
- [#5446](https://github.com/emberjs/data/pull/5446) [CLEANUP] fix model and factory lookup
- [#5466](https://github.com/emberjs/data/pull/5466) Serialize empty hasMany relationships
- [#5461](https://github.com/emberjs/data/pull/5461) [BUGFIX] update content of proxy for async belongs-to relationships when null data received
- [#5471](https://github.com/emberjs/data/pull/5471) [CHORE] cull unnecessary files left from previous build setups
- [#5476](https://github.com/emberjs/data/pull/5476) [Feature] added module-unification adapter and adapter-test blueprints
- [#5508](https://github.com/emberjs/data/pull/5508) [CHORE] Update Dependencies

### Release 3.2.0 (June 29, 2018)

- [#5497](https://github.com/emberjs/data/pull/5497) [BUGFIX] Make snapshot lazier and fix defaultValue.
- [#5499](https://github.com/emberjs/data/pull/5499) [BUGFIX] Backport fix infinite relationship retry issue from #5492.
- [#5508](https://github.com/emberjs/data/pull/5508) [CHORE] Update Dependencies to avoid `broccoli-funnel` deprecation.
- [#5432](https://github.com/emberjs/data/pull/5432) [CHORE] Remove `exists-sync` dependency.
- [#5436](https://github.com/emberjs/data/pull/5436) [CHORE] Remove all usage of `Ember.copy` to avoid future deprecation.
- [#5437](https://github.com/emberjs/data/pull/5437) / [#5459](https://github.com/emberjs/data/pull/5459) [CHORE] Removes deprecated `store.filter` feature, must migrate to `ember-data-filter@2.0.0` for similar API usage.
- [#5461](https://github.com/emberjs/data/pull/5461) [BUGFIX] Update content of proxy for async belongs-to relationships when null data received
- [#5467](https://github.com/emberjs/data/pull/5467) [BUGFIX] Avoid unnecessary work during destruction process.
- [#5439](https://github.com/emberjs/data/pull/5439) [FEAT] FASTBOOT SHOEBOX - Use actions queue so rehydration works
- [#5412](https://github.com/emberjs/data/pull/5412) Fix npmignore and cleanup test artifacts before publishing
- [#4977](https://github.com/emberjs/data/pull/4977) Trap exceptions that are thrown from adapter methods
- [#4856](https://github.com/emberjs/data/pull/4856) [BUGFIX #4497] query/queryRecord/filter now support adapter options
- [#5408](https://github.com/emberjs/data/pull/5408) [FEAT BUGFIX] enable canonical state updates to deleted records
- [#5336](https://github.com/emberjs/data/pull/5336) [CHORE] remove all benchmark related code
- [#5324](https://github.com/emberjs/data/pull/5324) Don't serialize new has many relationships
- [#5405](https://github.com/emberjs/data/pull/5405) [CHORE] remove dead methods left behind from ff removal
- [#5406](https://github.com/emberjs/data/pull/5406) [BUGFIX release] Fix `Model.modelName` inheritance with Ember 3.2+.
- [#5366](https://github.com/emberjs/data/pull/5366) fix initial polymorphic attribute
- [#5345](https://github.com/emberjs/data/pull/5345) Check if adapter#query is a wrapped function
- [#5385](https://github.com/emberjs/data/pull/5385) Use `najax` in `fastboot` and some refactoring to isolate `jQuery.ajax`
- [#5399](https://github.com/emberjs/data/pull/5399) Remove unneeded feature flagged tests
- [#5410](https://github.com/emberjs/data/pull/5410) [FEAT BUGFIX] resolves issues with links and data in relationships (#5410)
- [#5413](https://github.com/emberjs/data/pull/5413) [BUGFIX] Fix availability of properties in createRecord init
- [#5414](https://github.com/emberjs/data/pull/5414) [FEAT BUGFIX] adds adapterOptions ability to model.reload()
- [#5415](https://github.com/emberjs/data/pull/5415) make createRecord sync and remove unnecessary run usage in tests
- [#5416](https://github.com/emberjs/data/pull/5416) adds a more robust test around reload
- [#5418](https://github.com/emberjs/data/pull/5418) Limit CI runs on branches to master, beta, release
- [#5422](https://github.com/emberjs/data/pull/5422) [FEAT] Prevent async test leakage (feat. adds test waiters)
- [#4977](https://github.com/emberjs/data/pull/4977) Trap exceptions that are thrown from adapter methods and reject the (#4977)
- [#5379](https://github.com/emberjs/data/pull/5379) minor typo
- [#5382](https://github.com/emberjs/data/pull/5382) [FIX] update ember-cli-dependency-checker to avoid deprecation warning
- [#5371](https://github.com/emberjs/data/pull/5371) Upgrade to ember-cli-qunit 4.0 and replace ember-dev with ember-qunit… (#5371)
- [#5369](https://github.com/emberjs/data/pull/5369) [BUGFIX beta] Fix createRecord creating two records
- [#5375](https://github.com/emberjs/data/pull/5375) Remove jQuery usage from tests (#5375)
- [#5378](https://github.com/emberjs/data/pull/5378) [BUGFIX] resolve issues with RecordArray sync for peekAll (#5378)
- [#5381](https://github.com/emberjs/data/pull/5381) [FEAT BREAKING] remove globals build for 3.x (#5381)
- [#5383](https://github.com/emberjs/data/pull/5383) fix external ordered set dependency
- [#5384](https://github.com/emberjs/data/pull/5384) [FEAT] remove all stale feature flags (#5384)

### Release 3.1.1 (March 27, 2018)

- [#5383](https://github.com/emberjs/data/pull/5383) Remove '@ember/ordered-set' warning when building Ember Data

### Release 3.1.0 (March 26, 2018)

- [#5255](https://github.com/emberjs/data/pull/5255) [BUGFIX beta] Use native Map if present. (#5255)
- [#5367](https://github.com/emberjs/data/pull/5367) Update ember twiddle links to working versions (#5367)
- [#5370](https://github.com/emberjs/data/pull/5370) Fix failing test on master by adding an invalid inverse to trigger th…
- [#5372](https://github.com/emberjs/data/pull/5372) [BUGFIX beta] Use @ember/ordered-set to avoid deprecations.
- [#5376](https://github.com/emberjs/data/pull/5376) [bugfix beta] Fetch cancels unload
- [#5377](https://github.com/emberjs/data/pull/5377) invalidate link promise on inverse unload
- [#5341](https://github.com/emberjs/data/pull/5341) Avoid `isEmpty` for known object types.
- [#5230](https://github.com/emberjs/data/pull/5230) [BUGFIX] enable lazy-relationship payloads to work with polymorphic relationships
- [#5327](https://github.com/emberjs/data/pull/5327) [DOC] Fix Changelog release date for v2.11.0
- [#5310](https://github.com/emberjs/data/pull/5310) Remove `s3-put` and `cached-npm` scripts.
- [#5273](https://github.com/emberjs/data/pull/5273) client-side-delete semantics `unloadRecord`
- [#5330](https://github.com/emberjs/data/pull/5330) [CHORE] updates to benchmark harness
- [#5322](https://github.com/emberjs/data/pull/5322) Clean up a bunch of invalid yuidoc blocks that were causing warnings …
- [#5318](https://github.com/emberjs/data/pull/5318) Use Ember.computed in the headers examples to avoid ember eslint warning
- [#5311](https://github.com/emberjs/data/pull/5311) Avoid bower usage in config/ember-try.js
- [#5321](https://github.com/emberjs/data/pull/5321) Update some dependencies to clean up some noise when running yarn ins…
- [#5317](https://github.com/emberjs/data/pull/5317) Dont serialize new belongsTo records (#5317)
- [#5323](https://github.com/emberjs/data/pull/5323) Stop using deprecated vendor-prefix hook to inject enableoptionalfeat…
- [#5326](https://github.com/emberjs/data/pull/5326) Remove usages of enumerable observers
- [#5329](https://github.com/emberjs/data/pull/5329) bump rsvp
- [#5332](https://github.com/emberjs/data/pull/5332) [BUGFIX beta] Fix development build relationship caching.
- [#5333](https://github.com/emberjs/data/pull/5333) [DEV-BUGFIX] Fix instrumentation when running in production (#5333)
- [#5339](https://github.com/emberjs/data/pull/5339) Prevent build issues when linking ember-source.
- [#5340](https://github.com/emberjs/data/pull/5340) [BUGFIX beta] Update DS.Errors#unknownProperty to return `undefined`.
- [#5342](https://github.com/emberjs/data/pull/5342) Refactor Travis setup to leverage stages... (#5342)

### Release 3.0.2 (March 1, 2018)

- [#5230](https://github.com/emberjs/data/pull/5230) [BUGFIX] enable lazy-relationship payloads to work with polymorphic relationships

### Release 3.0.1 (February 13, 2018)

- [#5273](https://github.com/emberjs/data/pull/5273) client-side-delete semantics `unloadRecord`

### Release 3.0.0 (February 12, 2018)

- [#5296](https://github.com/emberjs/data/pull/5296) blueprints/adapter-test: Add RFC232 variants
- [#5249](https://github.com/emberjs/data/pull/5249) Fix client-side delete + resurrection
- [#5301](https://github.com/emberjs/data/pull/5301) Add a test to ensure multiple stores get unique instances of serializ…
- [#5289](https://github.com/emberjs/data/pull/5289) [CLEANUP beta] Remove support/deprecation for normalizeHash in 3.0.0 (#5289)
- [#5286](https://github.com/emberjs/data/pull/5286) Remove deprecation/support for complex object as defaultValues of DS.attr
- [#5288](https://github.com/emberjs/data/pull/5288) Remove date transforms deprecations and support for Ember.Date.parse
- [#5289](https://github.com/emberjs/data/pull/5289) [CLEANUP beta] Remove support/deprecation for normalizeHash in 3.0.0 (#5289)
- [#5261](https://github.com/emberjs/data/pull/5261) [BUGFIX] inverseFor should respect inverse: null
- [#5285](https://github.com/emberjs/data/pull/5285) Remove deprecation messages for old instance initializers
- [#5290](https://github.com/emberjs/data/pull/5290) Remove deprecation around shouldSerializeHasMany
- [#5291](https://github.com/emberjs/data/pull/5291) Remove deprecation and fallback for keyForAttribute when keyForPolymo…
- [#5293](https://github.com/emberjs/data/pull/5293) cleanup: node-tests cleanup (#5293)
- [#5294](https://github.com/emberjs/data/pull/5294) blueprints/transform-test: Add RFC232 variants
- [#5297](https://github.com/emberjs/data/pull/5297) bluepints/model-test: Add RFC232 variants
- [#5298](https://github.com/emberjs/data/pull/5298) blueprints/serializer-test: Add RFC232 variants
- [#5299](https://github.com/emberjs/data/pull/5299) Fixup the RFC232 model-test files.
- [#5300](https://github.com/emberjs/data/pull/5300) Simplify `store.adapterFor` and `store.serializerFor`.
- [#5305](https://github.com/emberjs/data/pull/5305) Serializers and adapters should be unique per store
- [#5308](https://github.com/emberjs/data/pull/5308) Simplify the getDescriptor test helper

### Release 2.18.3 (July 6, 2018)

- [#5519](https://github.com/emberjs/data/pull/5519) Do not publish `.node_modules.ember-try` folder to npm

### Release 2.18.2 (March 1, 2018)

- [#5230](https://github.com/emberjs/data/pull/5230) [BUGFIX] enable lazy-relationship payloads to work with polymorphic relationships

### Release 2.18.1 (February 13, 2018)

- [#5273](https://github.com/emberjs/data/pull/5273) client-side-delete semantics `unloadRecord`

### Release 2.18.0 (December 28, 2017)

- [#5225](https://github.com/emberjs/data/pull/5225) Remove blueprints for Mocha < 0.12. (#5225)
- [#4998](https://github.com/emberjs/data/pull/4998) [DOC beta] Assert that both modelName and id are passed to `peekRecord` (#4998)
- [#5223](https://github.com/emberjs/data/pull/5223) [BUGFIX release] Cleanup test only dependencies.
- [#5200](https://github.com/emberjs/data/pull/5200) bump rsvp
- [#5108](https://github.com/emberjs/data/pull/5108) Updates addon to adhere to RFC 176 (#5108)
- [#5232](https://github.com/emberjs/data/pull/5232) Update documentation in model.js
- [#5203](https://github.com/emberjs/data/pull/5203) Skip ember try on appveyor
- [#5239](https://github.com/emberjs/data/pull/5239) Deprecate support for "production like" values in EMBER_ENV
- [#5213](https://github.com/emberjs/data/pull/5213) [BUGFIX beta] proxy `meta` on PromiseArray
- [#5212](https://github.com/emberjs/data/pull/5212) Do not show feature flag improved-ajax methods in the api docs
- [#5206](https://github.com/emberjs/data/pull/5206) [BUGFIX beta] Fix broccoli-babel-transpiler cache warnings
- [#5216](https://github.com/emberjs/data/pull/5216) [BUGFIX beta] invalid record becomes loaded when property is reset
- [#5217](https://github.com/emberjs/data/pull/5217) [BUGFIX beta] RecordReference returns null when not yet loaded
- [#5218](https://github.com/emberjs/data/pull/5218) Update assert against nulls (#5218)
- [#5220](https://github.com/emberjs/data/pull/5220) Remove (unnecessary) ember-inflector peer dependency
- [#5221](https://github.com/emberjs/data/pull/5221) Fix docs link. (#5221)
- [#5224](https://github.com/emberjs/data/pull/5224) Add missing dependency for travis build
- [#5238](https://github.com/emberjs/data/pull/5238) Move initialize-store-service.js out of the instance-initializers dir…
- [#5242](https://github.com/emberjs/data/pull/5242) [BUGFIX beta] Normalize model names during `push`
- [#5250](https://github.com/emberjs/data/pull/5250) [doc] Update links to Ember Guide (#5250)
- [#5260](https://github.com/emberjs/data/pull/5260) [doc] Update urlForFindRecord example

### Release 2.17.1 (March 1, 2018)

- [#5230](https://github.com/emberjs/data/pull/5230) [BUGFIX] enable lazy-relationship payloads to work with polymorphic relationships

### Release 2.17.0 (November 19, 2017)

- [#5216](https://github.com/emberjs/data/pull/5216) [BUGFIX beta] invalid record becomes loaded when property is reset
- [#4998](https://github.com/emberjs/data/pull/4998) [DOC beta] Assert that both modelName and id are passed to `peekRecord` (#4998)
- [#5217](https://github.com/emberjs/data/pull/5217) [BUGFIX beta] RecordReference returns null when not yet loaded
- [#5166](https://github.com/emberjs/data/pull/5166) [DOC] Remove mention of `bower install` from README
- [#5114](https://github.com/emberjs/data/pull/5114) Make import stripping smarter to resolve #5019
- [#5165](https://github.com/emberjs/data/pull/5165) [DOC] Update README build step script name
- [#5212](https://github.com/emberjs/data/pull/5212) Do not show feature flag improved-ajax methods in the api docs
- [#5183](https://github.com/emberjs/data/pull/5183) [DOCS release] Add missing "relationship" field to RESTAdapter.findBelongsTo docs
- [#5176](https://github.com/emberjs/data/pull/5176) fix node 4
- [#5172](https://github.com/emberjs/data/pull/5172) [DOC] Remove parameter from BelongsToReference.value
- [#5178](https://github.com/emberjs/data/pull/5178) Ignore included resources without that don't have a corresponding ember-data model
- [#5213](https://github.com/emberjs/data/pull/5213) [BUGFIX beta] proxy `meta` on PromiseArray
- [#5197](https://github.com/emberjs/data/pull/5197) Fix ember-data Node 4.x builds
- [#5191](https://github.com/emberjs/data/pull/5191) Remove feature flagging for ds-extended-errors.
- [#5184](https://github.com/emberjs/data/pull/5184) Update LICENSE through 2017
- [#5196](https://github.com/emberjs/data/pull/5196) [BUGFIX beta] Avoid cache related warnings during builds.
- [#5206](https://github.com/emberjs/data/pull/5206) [BUGFIX beta] Fix broccoli-babel-transpiler cache warnings
- [#5216](https://github.com/emberjs/data/pull/5216) [BUGFIX beta] invalid record becomes loaded when property is reset
- [#5220](https://github.com/emberjs/data/pull/5220) Remove (unnecessary) ember-inflector peer dependency
- [#5223](https://github.com/emberjs/data/pull/5223) [BUGFIX release] Cleanup test only dependencies.
- [#5224](https://github.com/emberjs/data/pull/5224) Add missing dependency for travis build
- [#5232](https://github.com/emberjs/data/pull/5232) Update documentation in model.js

### Release 2.16.4 (March 1, 2018)

- [#5230](https://github.com/emberjs/data/pull/5230) [BUGFIX] enable lazy-relationship payloads to work with polymorphic relationships

### Release 2.16.1 (October 4, 2017)

- [#5114](https://github.com/emberjs/data/pull/5114) Make import stripping smarter to resolve #5019
- [#5197](https://github.com/emberjs/data/pull/5197) Fix ember-data Node 4.x builds
- [#5206](https://github.com/emberjs/data/pull/5206) [BUGFIX beta] Fix broccoli-babel-transpiler cache warnings

### Release 2.16.0 (October 3, 2017)

- [#5192](https://github.com/emberjs/data/pull/5192) Remove feature flagging for ds-extended-errors.
- [#4994](https://github.com/emberjs/data/pull/4994) [BUGFIX beta] Fix flushing of pending saves, that include a deleted record (#4994)
- [#5089](https://github.com/emberjs/data/pull/5089) Bump `amd-name-resolver` version to enable parallel babel transpile
- [#5030](https://github.com/emberjs/data/pull/5030) fix build
- [#5029](https://github.com/emberjs/data/pull/5029) loosen header parsing slightly
- [#5094](https://github.com/emberjs/data/pull/5094) {master} Unload fun
- [#5038](https://github.com/emberjs/data/pull/5038) remove deprecated `idToRecord` and cleanup
- [#5035](https://github.com/emberjs/data/pull/5035) [BUGFIX release] Fix global build (#5035)
- [#5031](https://github.com/emberjs/data/pull/5031) Ensure `ember-data/-private` module is emitted properly for ember-cli < 2.12. (#5031)
- [#5101](https://github.com/emberjs/data/pull/5101) [DOC beta] fix instructions for build command
- [#5047](https://github.com/emberjs/data/pull/5047) cleanup
- [#5039](https://github.com/emberjs/data/pull/5039) use prop destructor for Ember dependencies
- [#5040](https://github.com/emberjs/data/pull/5040) tests for unload + resurrect + remote relationship state
- [#5044](https://github.com/emberjs/data/pull/5044) update `ember-resolver` `loader.js` `rsvp`
- [#5115](https://github.com/emberjs/data/pull/5115) [DOC release] Fixes code blocks for api viewer
- [#5060](https://github.com/emberjs/data/pull/5060) Set hasData for preloaded empty hasMany
- [#5058](https://github.com/emberjs/data/pull/5058) [BUGFIX] keep local state after a deletion
- [#5049](https://github.com/emberjs/data/pull/5049) more cleanup
- [#5051](https://github.com/emberjs/data/pull/5051) add test for hasMany + addObject + destroyRecord
- [#5048](https://github.com/emberjs/data/pull/5048) [BUGFIX release] createRecord should only setup relationships it has … (#5048)
- [#5053](https://github.com/emberjs/data/pull/5053) [BUGFIX] has-many relationship: set hasData when fetching link
- [#5128](https://github.com/emberjs/data/pull/5128) Avoid MODEL_FACTORY_INJECTION deprecations in tests on Ember >= 2.14.
- [#5075](https://github.com/emberjs/data/pull/5075) unpin testem version
- [#5074](https://github.com/emberjs/data/pull/5074) disable node-tests in windows for now
- [#5072](https://github.com/emberjs/data/pull/5072) remove `pretender` and update some deps
- [#5066](https://github.com/emberjs/data/pull/5066) Revert "[BUGFIX] keep local state after a deletion"
- [#5067](https://github.com/emberjs/data/pull/5067) [BUGFIX] Preserve local relationship changes after persisting a delet…
- [#5070](https://github.com/emberjs/data/pull/5070) [DOC release] Update doc for deprecated function.
- [#5130](https://github.com/emberjs/data/pull/5130) Replace Ember.String.{pluralize,singularize} with ember-inflector imports
- [#5099](https://github.com/emberjs/data/pull/5099) {master} forward port
- [#5088](https://github.com/emberjs/data/pull/5088) {MASTER} [BUGFIX release] handle dupe relationship entries
- [#5077](https://github.com/emberjs/data/pull/5077) [BUGFIX release] fix destroyRecord followed by unloadRecord and impli…
- [#5141](https://github.com/emberjs/data/pull/5141) Import Inflector instead of relying on Ember namespace
- [#5110](https://github.com/emberjs/data/pull/5110) [BUGFIX beta] Implement `cacheKeyForTree` hook.
- [#5106](https://github.com/emberjs/data/pull/5106) {forwardport master}
- [#5147](https://github.com/emberjs/data/pull/5147) [BUGFIX release] fix relationship merging
- [#5126](https://github.com/emberjs/data/pull/5126) Failing test for #5125 and attempted fix
- [#5119](https://github.com/emberjs/data/pull/5119) Don't notify relationships with links during initialization
- [#5123](https://github.com/emberjs/data/pull/5123) Ensure we are properly testing multiple Ember versions.
- [#5122](https://github.com/emberjs/data/pull/5122) Remove Bower dependency and related files.
- [#5139](https://github.com/emberjs/data/pull/5139) [DOC release] Improve save method documentation
- [#5144](https://github.com/emberjs/data/pull/5144) [BUGFIX release] Load many2many relationships correctly
- [#5150](https://github.com/emberjs/data/pull/5150) [BUGFIX release] Enumerate relationships provided, not all on a given…
- [#5151](https://github.com/emberjs/data/pull/5151) [CLEANUP] PERF prevent duplicate recordArrayManager signals on push o…
- [#5153](https://github.com/emberjs/data/pull/5153) [BUGFIX release] ensure inverse async HasMany is correctly maintained
- [#5162](https://github.com/emberjs/data/pull/5162) Update RELEASE.md
- [#5192](https://github.com/emberjs/data/pull/5192) Remove feature flagging for ds-extended-errors.

### Release 2.15.4 (March 1, 2018)

- [#5230](https://github.com/emberjs/data/pull/5230) [BUGFIX] enable lazy-relationship payloads to work with polymorphic relationships

### Release 2.15.3 (September 30, 2017)

- [#5195](https://github.com/emberjs/data/pull/5195) Ensure `ember-data/-private` module is emitted properly for ember-cli…

### Release 2.15.2 (September 28, 2017)

- [#5193](https://github.com/emberjs/data/pull/5193) Remove feature flagging for ds-extended-errors.

### Release 2.15.1 (September 27, 2017)

- [#5188](https://github.com/emberjs/data/pull/5188) Backport to release

### Release 2.15.0 (September 1, 2017)

- [#5132](https://github.com/emberjs/data/pull/5132) [BUGFIX] Fixes saving a record immediately after unloading a record with the same id
- [#5145](https://github.com/emberjs/data/pull/5145) [BUGFIX] Load many2many relationships correctly
- [#5148](https://github.com/emberjs/data/pull/5148) [BUGFIX] Relationships now update properly with new information
- [#5155](https://github.com/emberjs/data/pull/5155) [BUGFIX] Ensure symmetry between async and sync relationships
- [#5098](https://github.com/emberjs/data/pull/5098) {beta} Beta unload and create
- [#5105](https://github.com/emberjs/data/pull/5105) {Beta} forward port
- [#5119](https://github.com/emberjs/data/pull/5119) [BUGFIX release] Don't notify relationships with links during initialization
- [#5033](https://github.com/emberjs/data/pull/5033) loosen header parsing slightly
- [#4965](https://github.com/emberjs/data/pull/4965) [BUGFIX beta] Skip test which doesn't play nicely with the latest em…
- [84041a5f](https://github.com/emberjs/data/commit/84041a5f73b5b2a8f6d6d6475f7aa71d5b83b939) Update RELEASE.md
- [#4959](https://github.com/emberjs/data/pull/4959) [BUGFIX] remove forgotten broccoli-stew import
- [#4947](https://github.com/emberjs/data/pull/4947) remove needless change events when creating a recordArrays
- [#5071](https://github.com/emberjs/data/pull/5071) [BACKPORT] Update doc for deprecated function.
- [#5002](https://github.com/emberjs/data/pull/5002) [BUGFIX BETA] Added `system/store/container-instance-cache` to the -private export
- [#4992](https://github.com/emberjs/data/pull/4992) Use https in references to emberjs website (#4992)
- [#4969](https://github.com/emberjs/data/pull/4969) [BUGFIX beta] Ensure Engines can boot without error.
- [#4971](https://github.com/emberjs/data/pull/4971) Fix typo in function call
- [#5008](https://github.com/emberjs/data/pull/5008) [BUGFIX BETA]: Fixed export regression. `ember-data/transform` to be default.
- [#5022](https://github.com/emberjs/data/pull/5022) Ensure `ember-data/-private` module is emitted properly for ember-cli < 2.12. (#5022)
- [#5031](https://github.com/emberjs/data/pull/5031) Ensure `ember-data/-private` module is emitted properly for ember-cli < 2.12. (#5031)
- [#5068](https://github.com/emberjs/data/pull/5068) [BUGFIX release] Preserve local relationship changes after persisting a delet…
- [#5079](https://github.com/emberjs/data/pull/5079) [BACKPORT 2 release] Release fix unload after destroy
- [#5086](https://github.com/emberjs/data/pull/5086) {release} [BUGFIX release] handle dupe relationship entries
- [#5091](https://github.com/emberjs/data/pull/5091) {release} Bump `amd-name-resolver` version to enable parallel babel transpile
- [#5092](https://github.com/emberjs/data/pull/5092) [BUGFIX release] relationship [x, y] should not break on x.unloadRecord()
- [#5032](https://github.com/emberjs/data/pull/5032) loosen header parsing slightly
- [#5048](https://github.com/emberjs/data/pull/5048) [BUGFIX release] createRecord should only setup relationships it has … (#5048)
- [#4981](https://github.com/emberjs/data/pull/4981) [DOC release] Document DS.HasManyReference.ids
- [#4964](https://github.com/emberjs/data/pull/4964) Fix typo: expect multiple s/methods/records back
- [#4959](https://github.com/emberjs/data/pull/4959) [BUGFIX] remove forgotten broccoli-stew import
- [#4960](https://github.com/emberjs/data/pull/4960) ensure we don't compile typeof checks poorly
- [#4962](https://github.com/emberjs/data/pull/4962) Update to use built-in debug code stripping functionality.
- [#4947](https://github.com/emberjs/data/pull/4947) remove needless change events when creating a recordArrays
- [#4984](https://github.com/emberjs/data/pull/4984) [DOC release] Fix doc for `diffArray`
- [#4971](https://github.com/emberjs/data/pull/4971) Fix typo in function call
- [#4965](https://github.com/emberjs/data/pull/4965) [BUGFIX beta] Skip test which doesn't play nicely with the latest em…
- [#4969](https://github.com/emberjs/data/pull/4969) [BUGFIX beta] Ensure Engines can boot without error.
- [#4978](https://github.com/emberjs/data/pull/4978) Lock ember-cli-htmlbars to 1.3.0 to get the build passing again
- [#4980](https://github.com/emberjs/data/pull/4980) [DOC release] Docs for has-many, belongs-to ref meta
- [#5002](https://github.com/emberjs/data/pull/5002) [BUGFIX BETA] Added `system/store/container-instance-cache` to the -private export
- [#5003](https://github.com/emberjs/data/pull/5003) Change setupStore helper default serializer to JSONAPISerializer #4754 (#5003)
- [#5008](https://github.com/emberjs/data/pull/5008) [BUGFIX BETA]: Fixed export regression. `ember-data/transform` to be default.
- [#5009](https://github.com/emberjs/data/pull/5009) cleanup `index.js` and drop `0.12` node
- [#5011](https://github.com/emberjs/data/pull/5011) Fix and tests for unloadRecord => findRecord issue

### Release 2.14.11 (February 28, 2018)

- [#5230](https://github.com/emberjs/data/pull/5230) [BUGFIX] enable lazy-relationship payloads to work with polymorphic relationships

### Release 2.14.10 (August 10, 2017)

- [#5119](https://github.com/emberjs/data/pull/5119) [BUGFIX release] Don't notify relationships with links during initialization

### Release 2.14.9 (July 29, 2017)

- [#5097](https://github.com/emberjs/data/pull/5102) [BUGFIX release] unloadRecord + findRecord + orphaned relationships

### Release 2.14.8 (July 28, 2017)

- [#5097](https://github.com/emberjs/data/pull/5097) [BUGFIX release] restore unloadRecord + createRecord

### Release 2.14.7 (July 25, 2017)

- [#5086](https://github.com/emberjs/data/pull/5086) {release} [BUGFIX release] handle dupe relationship entries
- [#5091](https://github.com/emberjs/data/pull/5091) {release} Bump `amd-name-resolver` version to enable parallel babel transpile
- [#5092](https://github.com/emberjs/data/pull/5092) [BUGFIX release] relationship [x, y] should not break on x.unloadRecord()

### Release 2.14.6 (July 25, 2017)

- [#5086](https://github.com/emberjs/data/pull/5086) {release} [BUGFIX release] handle dupe relationship entries
- [#5091](https://github.com/emberjs/data/pull/5091) {release} Bump `amd-name-resolver` version to enable parallel babel transpile
- [#5092](https://github.com/emberjs/data/pull/5092) [BUGFIX release] relationship [x, y] should not break on x.unloadRecord()

### Release 2.14.5 (July 20, 2017)

- [#5031](https://github.com/emberjs/data/pull/5031) Ensure `ember-data/-private` module is emitted properly for ember-cli < 2.12. (#5031)
- [#5079](https://github.com/emberjs/data/pull/5079) [BACKPORT 2 release] Release fix unload after destroy

### Release 2.14.4 (July 11, 2017)

- [#5048](https://github.com/emberjs/data/pull/5048) [BUGFIX release] createRecord should only setup relationships it has … (#5048)

### Release 2.14.3 (June 22, 2017)

- [#5033](https://github.com/emberjs/data/pull/5033) loosen header parsing slightly

### Release 2.14.2 (June 19, 2017)

- [#5022](https://github.com/emberjs/data/pull/5022) Ensure `ember-data/-private` module is emitted properly for ember-cli < 2.12. (#5022)

### Release 2.14.1 (June 19, 2017)

- [#4994](https://github.com/emberjs/data/pull/4994) [BUGFIX beta] Fix flushing of pending saves, that include a deleted record (#4994)
- [#5008](https://github.com/emberjs/data/pull/5008) [BUGFIX BETA]: Fixed export regression. `ember-data/transform` to be default.

### Release 2.14.0 (June 18, 2017)

- [#5013](https://github.com/emberjs/data/pull/5013) [BUGFIX beta] fixes an issue with sync dematerialization followed by a findRecord, adds test coverage
- [#5002](https://github.com/emberjs/data/pull/5002) [BUGFIX BETA] Added `system/store/container-instance-cache` to the -private export file
- [#4959](https://github.com/emberjs/data/pull/4959) [BUGFIX] remove forgotten broccoli-stew import
- [#4965](https://github.com/emberjs/data/pull/4965) [BUGFIX beta] Skip test which doesn't play nicely with the latest em…
- [#4969](https://github.com/emberjs/data/pull/4969) [BUGFIX beta] Ensure Engines can boot without error.
- [#4971](https://github.com/emberjs/data/pull/4971) Fix typo in function call
- [#4885](https://github.com/emberjs/data/pull/4885) Lazy snapshot.type
- [#4855](https://github.com/emberjs/data/pull/4855) Update the changelog for the Ember Data 2.12.0 release
- [#4821](https://github.com/emberjs/data/pull/4821) Pay go setup relationships
- [#4884](https://github.com/emberjs/data/pull/4884) Defer serializer loading
- [#4863](https://github.com/emberjs/data/pull/4863) Tidy up parse-reponse-headers (#4863)
- [#4861](https://github.com/emberjs/data/pull/4861) Update yarn.lock
- [#4862](https://github.com/emberjs/data/pull/4862) Babel 6
- [#4860](https://github.com/emberjs/data/pull/4860) Refactor the detection / warnings around ember-cli-shims. (#4860)
- [#4913](https://github.com/emberjs/data/pull/4913) [BUGFIX canary] don't prematurely nullify props
- [#4869](https://github.com/emberjs/data/pull/4869) Speed up triggering events
- [#4864](https://github.com/emberjs/data/pull/4864) make ES6.Classes loose (#4864)
- [#4868](https://github.com/emberjs/data/pull/4868) [PERF] make filtered/liveRecord array storage a simple Object.create(…
- [#4909](https://github.com/emberjs/data/pull/4909) Deprecate didUpdateAll, add \_didUpdateAll.
- [#4870](https://github.com/emberjs/data/pull/4870) More record -> internalModel fixes
- [#4908](https://github.com/emberjs/data/pull/4908) Add a better error message when malformatted JSON API is pushed into …
- [#4871](https://github.com/emberjs/data/pull/4871) Remove dead code
- [#4891](https://github.com/emberjs/data/pull/4891) Add a test to ensure a HasManyReference returns a value when the arra…
- [#4905](https://github.com/emberjs/data/pull/4905) [DOCUMENTATION] Refer the RFC process for requesting new features
- [#4896](https://github.com/emberjs/data/pull/4896) Ember.warn when ManyArray.objectAt() is undefined
- [#4892](https://github.com/emberjs/data/pull/4892) [DOC] Documents the caching behavior of queryRecord
- [#4900](https://github.com/emberjs/data/pull/4900) [doc] updating peekRecord documentation with reference to its counterpart f…
- [#4893](https://github.com/emberjs/data/pull/4893) Remove unnecessary relationship guard
- [#4897](https://github.com/emberjs/data/pull/4897) Deprecate buildInternalModel, add \_buildInternalModel.
- [#4898](https://github.com/emberjs/data/pull/4898) [BUGFIX beta] Rename `relationship.destroy` to `removeInverseRelationships`
- [#4901](https://github.com/emberjs/data/pull/4901) [BUGFIX beta] Removes `get record` from InternalModel. (#4901)
- [#4899](https://github.com/emberjs/data/pull/4899) Fix internalModel typo
- [#4903](https://github.com/emberjs/data/pull/4903) Use node 6 for travis tests
- [#4880](https://github.com/emberjs/data/pull/4880) [BUGFIX canary] ensure context is applied in the iife
- [#4878](https://github.com/emberjs/data/pull/4878) Fix tests in release branch RE: factoryFor. (#4878)
- [#4874](https://github.com/emberjs/data/pull/4874) Rename record[s] -> internalModel[s]
- [#4883](https://github.com/emberjs/data/pull/4883) Fix readme typo - "First things first"
- [#4876](https://github.com/emberjs/data/pull/4876) [BUGFIX canary] ensure the globals build has the correct context in the iife.
- [#4895](https://github.com/emberjs/data/pull/4895) [PERF] single-pass over the initializers array
- [#4931](https://github.com/emberjs/data/pull/4931) [BUGFIX beta][fixes #4509] createRecord initializes correctly
- [#4914](https://github.com/emberjs/data/pull/4914) Revert "Ember.warn when ManyArray.objectAt() is underfined"
- [#4910](https://github.com/emberjs/data/pull/4910) [BUGFIX] initial-relationship-setup must handle null
- [#4911](https://github.com/emberjs/data/pull/4911) [BUGFIX] partially fix pushing of null onto already materialized array
- [#4935](https://github.com/emberjs/data/pull/4935) bump github module slightly to work around node-resolve issue (remove…
- [#4922](https://github.com/emberjs/data/pull/4922) [BUGFIX release] restore internalModels GUID_KEY’s
- [#4920](https://github.com/emberjs/data/pull/4920) Svelted some our builds a bit (3KB savings)
- [#4919](https://github.com/emberjs/data/pull/4919) [DOC] Fix findHasMany parameter order
- [#4925](https://github.com/emberjs/data/pull/4925) [SVELTE] rollup -private for winnings
- [#4924](https://github.com/emberjs/data/pull/4924) [PERF] Model.prototype.didDefineProperty only in dev
- [#4943](https://github.com/emberjs/data/pull/4943) hash-for-dep only the plugin (not all of ember-data) as this plugin h…
- [#4928](https://github.com/emberjs/data/pull/4928) Don't use `let` or `const`
- [#4926](https://github.com/emberjs/data/pull/4926) [DOC release] Add missing ` in urlsForFindMany description
- [#4930](https://github.com/emberjs/data/pull/4930) Remove no-longer-working private API usage.
- [#4932](https://github.com/emberjs/data/pull/4932) update yarn.lock
- [#4936](https://github.com/emberjs/data/pull/4936) [SVELTE] Transforms & remove Date.parse polyfill (#4936)
- [#4937](https://github.com/emberjs/data/pull/4937) [BUGFIX beta] Update dependencies to use Babel 6.
- [#4941](https://github.com/emberjs/data/pull/4941) only coerce non-string id's
- [#4946](https://github.com/emberjs/data/pull/4946) dummy app routes should work with and without heimdall
- [#4948](https://github.com/emberjs/data/pull/4948) Only will merge mixin in dev
- [#4950](https://github.com/emberjs/data/pull/4950) [PERF] Guard against poorly optimized babel output

### Release 2.13.2 (June 18, 2017)

- [#5012](https://github.com/emberjs/data/pull/5012) [BUGFIX release] fixes an issue with sync dematerialization followed by a findRecord, adds test coverage

### Release 2.13.1 (May 5, 2017)

- [#4965](https://github.com/emberjs/data/pull/4965) [BUGFIX beta] Skip test which doesn't play nicely with the latest em…
- [#4970](https://github.com/emberjs/data/pull/4970) [BUGFIX release] Ensure Engines can boot without error.

### Release 2.13.0 (April 28, 2017)

- [#4860](https://github.com/emberjs/data/pull/4860) Refactor the detection / warnings around ember-cli-shims.
- [#4853](https://github.com/emberjs/data/pull/4853) [Fixes #4853] use Object.create(null) directly
- [#4858](https://github.com/emberjs/data/pull/4858) [PERF] let GUID_KEYS just be set on the model instances
- [#4937](https://github.com/emberjs/data/pull/4937) [BUGFIX beta] Update dependencies to use Babel 6
- [#4922](https://github.com/emberjs/data/pull/4922) [BUGFIX release] restore internalModels GUID_KEY’s
- [#4916](https://github.com/emberjs/data/pull/4916) [BACKPORT 4913] don't prematurely nullify props on the container-inst…
- [#4862](https://github.com/emberjs/data/pull/4862) [BETA] Update dependencies to use babel 6.
- [#4877](https://github.com/emberjs/data/pull/4877) [BUGFIX beta] ensure the globals build has the correct context in the iife.
- [#4879](https://github.com/emberjs/data/pull/4879) [BUGFIX beta] ensure context is applied in iife
- [#4767](https://github.com/emberjs/data/pull/4767) Updating gitignore to remove .idea
- [#4741](https://github.com/emberjs/data/pull/4741) Clean up some YUIdoc erros
- [#4693](https://github.com/emberjs/data/pull/4693) Fixed modelFor documentation. Look up model's class name (#4693)
- [#4719](https://github.com/emberjs/data/pull/4719) [DOC release] Add note to embedded records mixin (#4719)
- [#4723](https://github.com/emberjs/data/pull/4723) Simplify Backburner Usage (#4723)
- [#4715](https://github.com/emberjs/data/pull/4715) converts Snapshot to an es6 class instead of using prototype assign
- [#4728](https://github.com/emberjs/data/pull/4728) [CLEANUP beta] Linter changes for addon, addon/adapters and addon/serializers
- [#4708](https://github.com/emberjs/data/pull/4708) es6 RecordArrayManager
- [#4657](https://github.com/emberjs/data/pull/4657) Deprecate unused initializers
- [#4593](https://github.com/emberjs/data/pull/4593) Free up `internalModel`s
- [#4729](https://github.com/emberjs/data/pull/4729) [CLEANUP Beta] Linter changes for addon/-private (not -private/system)
- [#4730](https://github.com/emberjs/data/pull/4730) [CLEANUP Beta] Linter changes for addon/-private/system
- [#4799](https://github.com/emberjs/data/pull/4799) [DOC] Add Ember imports and use lets in adapter examples
- [#4760](https://github.com/emberjs/data/pull/4760) Update deprecate arguments (#4760)
- [#4743](https://github.com/emberjs/data/pull/4743) [BUGFIX canary] Fix \_lookupFactory deprecation for Ember canary
- [#4747](https://github.com/emberjs/data/pull/4747) Updates code sample to match Guides
- [#4750](https://github.com/emberjs/data/pull/4750) Add a yarn lock file
- [#4745](https://github.com/emberjs/data/pull/4745) License: 2017
- [#4808](https://github.com/emberjs/data/pull/4808) Avoid mutating model factory in \_modelForMixin.
- [#4772](https://github.com/emberjs/data/pull/4772) [DOC] Shorthand method syntax, quotes, and cleanup
- [#4766](https://github.com/emberjs/data/pull/4766) [DOC] Update store.unloadRecord description
- [#4763](https://github.com/emberjs/data/pull/4763) Document cache/request behavior of `query` #4733 (#4763)
- [#4771](https://github.com/emberjs/data/pull/4771) [BUGFIX beta] Ensure ISO-8601 regex correctly matches timestamps (#4771)
- [#4765](https://github.com/emberjs/data/pull/4765) [DOC] Make model.unloadRecord public (#4765)
- [#4762](https://github.com/emberjs/data/pull/4762) [DOC] - add bower install to README
- [#4769](https://github.com/emberjs/data/pull/4769) [DOC release] Add missing docs for `preload` option.
- [#4815](https://github.com/emberjs/data/pull/4815) More Cleanups
- [#4780](https://github.com/emberjs/data/pull/4780) [DOC] shorthand method and quotes/semicolons for serializers/json
- [#4778](https://github.com/emberjs/data/pull/4778) [DOC] shorthand methods and quotes for json-api serializer (#4778)
- [#4775](https://github.com/emberjs/data/pull/4775) [DOC] shorthand methods for transform
- [#4774](https://github.com/emberjs/data/pull/4774) [DOC] Shorthand method fixes in adapter
- [#4776](https://github.com/emberjs/data/pull/4776) [DOC] shorthand method fixes for serializer
- [#4777](https://github.com/emberjs/data/pull/4777) [DOC] shorthand method in attr
- [#4832](https://github.com/emberjs/data/pull/4832) remove isPrimaryType’s reliance on modelName (#4832)
- [#4794](https://github.com/emberjs/data/pull/4794) Fix spelling error in documentation
- [#4782](https://github.com/emberjs/data/pull/4782) [DOC] shorthand methods and quotes for adapter errors
- [#4781](https://github.com/emberjs/data/pull/4781) [DOC] shorthand method and quotes fro serializers/rest
- [#4789](https://github.com/emberjs/data/pull/4789) Do not access container if Ember.getOwner exists.
- [#4790](https://github.com/emberjs/data/pull/4790) Add a test for #4770
- [#4783](https://github.com/emberjs/data/pull/4783) [DOC] shorthand methods for rest adapter
- [#4837](https://github.com/emberjs/data/pull/4837) Stefs cleanup (#4837)
- [#4810](https://github.com/emberjs/data/pull/4810) [Fixes #4807] realize class + factory seperation
- [#4809](https://github.com/emberjs/data/pull/4809) bump ember-cli
- [#4805](https://github.com/emberjs/data/pull/4805) Don’t redefine findPossibleInverses for each \_findInverseFor
- [#4806](https://github.com/emberjs/data/pull/4806) Added missing DS references to DS.Model implementation examples
- [#4798](https://github.com/emberjs/data/pull/4798) [DOC] Cleanup example code in attr
- [#4841](https://github.com/emberjs/data/pull/4841) Cleanup (#4841)
- [#4830](https://github.com/emberjs/data/pull/4830) don’t create extra internal promise objects
- [#4823](https://github.com/emberjs/data/pull/4823) [BUGFIX] ensure all of DS is initialized together
- [#4813](https://github.com/emberjs/data/pull/4813) misc cleanup (#4813)
- [#4818](https://github.com/emberjs/data/pull/4818) remove more unneeded class reification
- [#4831](https://github.com/emberjs/data/pull/4831) Cleanup things and stuff (#4831)
- [#4836](https://github.com/emberjs/data/pull/4836) cleanup + reject with useful reasons
- [#4838](https://github.com/emberjs/data/pull/4838) Stefs cleanup (and some test suite memory leak fixes) (#4838)
- [#4840](https://github.com/emberjs/data/pull/4840) [DOC] Fix markup for example code of `DS.Model#inverseFor`
- [#4842](https://github.com/emberjs/data/pull/4842) Stable has many promise proxy (#4842)
- [#4846](https://github.com/emberjs/data/pull/4846) remove un-needed Ember.A
- [#4850](https://github.com/emberjs/data/pull/4850) Optimise has many notifications (#4850)
- [#4851](https://github.com/emberjs/data/pull/4851) Don't calculate `_changedKeys` pointlessly (#4851)

### Release 2.12.2 (April 12, 2017)

- [#4922](https://github.com/emberjs/data/pull/4922) [BUGFIX release] restore internalModels GUID_KEY’s
- [#4917](https://github.com/emberjs/data/pull/4917) [BACKPORT 4913] For release

### Release 2.12.1 (March 17, 2017)

- [#4875](https://github.com/emberjs/data/pull/4875) [BUGFIX release] ensure the globals build has the correct context in the iife.
- [#4881](https://github.com/emberjs/data/pull/4881) Fix injection-test on the release branch

### Release 2.12.0 (March 13, 2017)

- [#4805](https://github.com/emberjs/data/pull/4805) Don’t redefine findPossibleInverses for each \_findInverseFor
- [#4808](https://github.com/emberjs/data/pull/4808) Avoid mutating model factory in \_modelForMixin.
- [#4810](https://github.com/emberjs/data/pull/4810) [Fixes #4807] realize class + factory seperation
- [#4743](https://github.com/emberjs/data/pull/4743) [BUGFIX canary] Fix \_lookupFactory deprecation for Ember canary
- [#4765](https://github.com/emberjs/data/pull/4765) [DOC] Make model.unloadRecord public (#4765)
- [#4792](https://github.com/emberjs/data/pull/4792) [BUGFIX beta] revert deletion of filter that removed deleted model…
- [#4789](https://github.com/emberjs/data/pull/4789) Do not access container if Ember.getOwner exists.
- [#4760](https://github.com/emberjs/data/pull/4760) Update deprecate arguments (#4760)
- [#4698](https://github.com/emberjs/data/pull/4698) [FIX backburner] Avoids spinning up unnecessary run loops via run.join
- [#4638](https://github.com/emberjs/data/pull/4638) Update the API docs for snapshots
- [#4705](https://github.com/emberjs/data/pull/4705) Underscores the already private store.reloadRecord method
- [#4663](https://github.com/emberjs/data/pull/4663) Silence warnings and deprecations in the console during tests
- [#4642](https://github.com/emberjs/data/pull/4642) Add API docs for the HasManyReference
- [#4706](https://github.com/emberjs/data/pull/4706) Improved performance for findHasMany finder
- [#4684](https://github.com/emberjs/data/pull/4684) Modernizes relationship containers
- [#4664](https://github.com/emberjs/data/pull/4664) Upgraded IdentityMap and RecordMap
- [#4668](https://github.com/emberjs/data/pull/4668) [PERF] use micro-queue
- [#4699](https://github.com/emberjs/data/pull/4699) include related record on the complex test
- [#4688](https://github.com/emberjs/data/pull/4688) Fixed a typo
- [#4685](https://github.com/emberjs/data/pull/4685) [FEATURE ds-rollback-attribute] rename ds-reset-attribute
- [#4686](https://github.com/emberjs/data/pull/4686) [FEATURE ds-improved-ajax] Disable feature
- [#4704](https://github.com/emberjs/data/pull/4704) Factory cache
- [#4696](https://github.com/emberjs/data/pull/4696) fix(benchmarks): benchmarks for store.query no longer included record…
- [#4691](https://github.com/emberjs/data/pull/4691) [BUGFIX beta] Add blueprints for "ember-cli-mocha >= 0.12.0"
- [#4697](https://github.com/emberjs/data/pull/4697) chore(benchmarks): benchmarks needed to time a few lookups for us to …
- [#4701](https://github.com/emberjs/data/pull/4701) [PERF] flatten DS.Model to avoid multi-extend, expensive reopens, and extra mixin detection
- [#4702](https://github.com/emberjs/data/pull/4702) Enable the ds-check-should-serialize-relationships feature flag
- [#4703](https://github.com/emberjs/data/pull/4703) Removes store.\_adapterRun
- [#4716](https://github.com/emberjs/data/pull/4716) [DOC canary] Updating CONTRIBUTING.md to use ember-twiddle as examples
- [#4718](https://github.com/emberjs/data/pull/4718) [BUGFIX beta] Inverse null relationships should throw if model doesn't exist 3
- [#4734](https://github.com/emberjs/data/pull/4734) [DOC] fix a couple of typos in model class docs
- [#4739](https://github.com/emberjs/data/pull/4739) Removed id in urlForFindAll signature

### Release 2.11.0 (January 9, 2017)

- [#4518](https://github.com/emberjs/data/pull/4518) Update the relationship docs to remove some references to a globals s…
- [#4581](https://github.com/emberjs/data/pull/4581) [DOC] Update descriptions of findRecord() and findAll()
- [#4438](https://github.com/emberjs/data/pull/4438) add `relationship` property to findHasMany RESTAdapter docs
- [#4283](https://github.com/emberjs/data/pull/4283) Add better error messaging for adapters that do not implement createR…
- [#4440](https://github.com/emberjs/data/pull/4440) Add examples to the Serializer API docs
- [#4272](https://github.com/emberjs/data/pull/4272) [BUGFIX beta] Don't unnecessarily materialize records
- [#4562](https://github.com/emberjs/data/pull/4562) [PERF] make internal model lazier
- [#4601](https://github.com/emberjs/data/pull/4601) Naming cleanup
- [#4586](https://github.com/emberjs/data/pull/4586) Remove the ds-boolean-transform-allow-null feature flag
- [#4582](https://github.com/emberjs/data/pull/4582) tidy up integration/filter-test
- [#4585](https://github.com/emberjs/data/pull/4585) Update changelog for the Ember Data 2.9.0 release
- [#4632](https://github.com/emberjs/data/pull/4632) [DOC ds-extended-errors] Add docs for extended errors
- [#4592](https://github.com/emberjs/data/pull/4592) [DOC] Add documentation for query#update() to refresh query
- [#4591](https://github.com/emberjs/data/pull/4591) Cleanup record array manager
- [#4587](https://github.com/emberjs/data/pull/4587) Remove ds-links-in-record-array feature flag
- [#4590](https://github.com/emberjs/data/pull/4590) Fix YUIDoc warnings
- [#4589](https://github.com/emberjs/data/pull/4589) Feat/improved cache
- [#4640](https://github.com/emberjs/data/pull/4640) build ember-data attribute debug info dynamically
- [#4606](https://github.com/emberjs/data/pull/4606) fix(instrumentation): heimdall-query needed bumped to work properly
- [#4599](https://github.com/emberjs/data/pull/4599) Don't warn for 'async: false' relationships with link + data
- [#4594](https://github.com/emberjs/data/pull/4594) Revert "unloadRecord does not remove observers"
- [#4605](https://github.com/emberjs/data/pull/4605) Don't notify belongsTo changes if nothing changed
- [#4597](https://github.com/emberjs/data/pull/4597) Cleanup record array manager
- [#4598](https://github.com/emberjs/data/pull/4598) fix integration/record-array-test setup
- [#4600](https://github.com/emberjs/data/pull/4600) make DS.ManyArray lazy
- [#4603](https://github.com/emberjs/data/pull/4603) [WARNING] Warn when extending JSONAPISerializer with extractMeta
- [#4604](https://github.com/emberjs/data/pull/4604) Warn when findRecord returns a different id than the one requested
- [#4659](https://github.com/emberjs/data/pull/4659) Document the relationship serialized format in the RESTAdapter
- [#4624](https://github.com/emberjs/data/pull/4624) Test assertions when updateRecord & deleteRecord don't exist on adapter
- [#4612](https://github.com/emberjs/data/pull/4612) [DOC] Mark `errorsHashToArray` and `errorsArrayToHash` public
- [#4620](https://github.com/emberjs/data/pull/4620) [FEATURE ds-serialize-id] add serializeId to json-serializer
- [#4613](https://github.com/emberjs/data/pull/4613) Assert that InternalModel is indeed not materialized on store.\_push
- [#4616](https://github.com/emberjs/data/pull/4616) Assert when original and not normalized key is found in payload
- [#4621](https://github.com/emberjs/data/pull/4621) tidy-up integration/filter-test
- [#4617](https://github.com/emberjs/data/pull/4617) chore(store): cleans up and optimizes code paths around fetching rela…
- [#4607](https://github.com/emberjs/data/pull/4607) Fix dummy app serializer
- [#4609](https://github.com/emberjs/data/pull/4609) [DOC] Improve warning for mismatched id in store.findRecord
- [#4614](https://github.com/emberjs/data/pull/4614) [DOC] Minor changes to addon/serializer.js
- [#4671](https://github.com/emberjs/data/pull/4671) Fix typo in delete-record-test
- [#4645](https://github.com/emberjs/data/pull/4645) cleanup system/many-array
- [#4636](https://github.com/emberjs/data/pull/4636) Add a missing example to the ManyArray api docs
- [#4630](https://github.com/emberjs/data/pull/4630) Updates json-api-mock-server
- [#4644](https://github.com/emberjs/data/pull/4644) [PERF] HasMany doesn't need to inform RecordArrayManager
- [#4629](https://github.com/emberjs/data/pull/4629) [DOC] #4595 revise unloadAll description
- [#4641](https://github.com/emberjs/data/pull/4641) Add API docs for the RecordReference
- [#4639](https://github.com/emberjs/data/pull/4639) Update API docs for BelongsToReference
- [#4643](https://github.com/emberjs/data/pull/4643) [BUGFIX #4649 #4648]
- [#4637](https://github.com/emberjs/data/pull/4637) Simplify Adapter#serialize by using snapshot.serialize() since they d…
- [#4661](https://github.com/emberjs/data/pull/4661) dirty check to prevent liveRecordArrays being rebuilt too often
- [#4665](https://github.com/emberjs/data/pull/4665) Deprecate store.recordIsLoaded
- [#4654](https://github.com/emberjs/data/pull/4654) remove useless private api
- [#4653](https://github.com/emberjs/data/pull/4653) Update the API docs on the JSONAPISerializer
- [#4652](https://github.com/emberjs/data/pull/4652) Improve the API docs for the JSONAPI adapter
- [#4662](https://github.com/emberjs/data/pull/4662) Code Cleanup for store.js
- [#4651](https://github.com/emberjs/data/pull/4651) Add some minor updates to the store documentation
- [#4658](https://github.com/emberjs/data/pull/4658) Test for hasMany array removal on deletion
- [#4669](https://github.com/emberjs/data/pull/4669) fix mock server
- [#4674](https://github.com/emberjs/data/pull/4674) Update `findHasMany` API docs
- [#4680](https://github.com/emberjs/data/pull/4680) Remove unused helper function `normalizeAttributes`

### Release 2.10.0 (November 28, 2016)

- [#4656](https://github.com/emberjs/data/pull/4656) [PERF backport to beta] fix sub-optimal compiler output ([#4655](https://github.com/emberjs/data/pull/4655))
- [#4592](https://github.com/emberjs/data/pull/4592) [DOC] Add documentation for query#update() to refresh query
- [#4510](https://github.com/emberjs/data/pull/4510) Heimdall instrumentation
- [#4546](https://github.com/emberjs/data/pull/4546) Revert "Log an assertion if the response from createRecord does not have an i…"
- [#4553](https://github.com/emberjs/data/pull/4553) [DOCS] Fix store.unloadAll modelName param type
- [#4566](https://github.com/emberjs/data/pull/4566) Properly cleanup store and env in store integration test
- [#4574](https://github.com/emberjs/data/pull/4574) Move heimdalljs to dependencies
- [#4576](https://github.com/emberjs/data/pull/4576) [DOC] Update Readme to reflect new default adapter
- [#4578](https://github.com/emberjs/data/pull/4578) Improved null id assertions

### Release 2.9.0 (October 18, 2016)

- [#4577](https://github.com/emberjs/data/pull/4577) [DOC] fix typo
- [#4529](https://github.com/emberjs/data/pull/4529) isUpdating should be true only if a reload happens
- [#4566](https://github.com/emberjs/data/pull/4566) Properly cleanup store and env in store integration test
- [#4567](https://github.com/emberjs/data/pull/4567) [bugfix beta] Treat status code 0 as an abort
- [#4559](https://github.com/emberjs/data/pull/4559) [BUGFIX beta] Use Ember.guidFor to set InternalModel's guid.
- [#4560](https://github.com/emberjs/data/pull/4560) [BUGFIX beta] Ensure record array length is reset during willDestroy.
- [#4545](https://github.com/emberjs/data/pull/4545) [BUGFIX beta] Make `Model#data` a plain getter.
- [#4541](https://github.com/emberjs/data/pull/4541) [DOC beta] Remove `Ember.ArrayController` from initializer example (#4540)
- [#4540](https://github.com/emberjs/data/pull/4540) Add examples to the build-url-mixin API docs (#4512)
- [#4537](https://github.com/emberjs/data/pull/4537) [BUGFIX beta] Ember Data should not swallow exceptions from the run loop
- [#4546](https://github.com/emberjs/data/pull/4546) Revert "Log an assertion if the response from createRecord does not have an i…"
- [#4536](https://github.com/emberjs/data/pull/4536) [DOC] fix features response typo (#4530)
- [#4490](https://github.com/emberjs/data/pull/4490) [DOCS] No need to use Ember.run in succes and failure of wrapped getJSON
- [#4493](https://github.com/emberjs/data/pull/4493) Addresses #4492
- [#4503](https://github.com/emberjs/data/pull/4503) Update ember-try config to test against alpha.
- [#4515](https://github.com/emberjs/data/pull/4515) Document the allowNull property on the boolean transform
- [#4516](https://github.com/emberjs/data/pull/4516) Update the docs for normalizeModelName so they explain the intent of …
- [#4521](https://github.com/emberjs/data/pull/4521) Remove ContainerProxy
- [#4522](https://github.com/emberjs/data/pull/4522) add license to bower.json

### Release 2.8.1 (September 23, 2016)

- [#4536](https://github.com/emberjs/data/pull/4536) bump to latest ember-cli, run ember init, cleanup post init
- [#4546](https://github.com/emberjs/data/pull/4546) Revert "Log an assertion if the response from createRecord does not have an I…"
- [#4537](https://github.com/emberjs/data/pull/4537) [BUGFIX beta] Ember Data should not swallow exceptions from the run loop
- [#4545](https://github.com/emberjs/data/pull/4545) [BUGFIX beta] Make `Model#data` a plain getter.
- [#4541](https://github.com/emberjs/data/pull/4541) [BUGFIX release] Include initializers for global production build

### Release 2.8.0 (September 8, 2016)

- [#4464](https://github.com/emberjs/data/pull/4464) Add benchmarks directory to npmignore
- [#4425](https://github.com/emberjs/data/pull/4425) [BUGFIX] Pass options to transform for serialization in json-api
- [#4408](https://github.com/emberjs/data/pull/4408) Log an assertion if the response from createRecord does not have an id and the id was not already provided by the client
- [#4246](https://github.com/emberjs/data/pull/4246) [FEATURE ds-rollback-attribute] Add rolling back of a single model attribute
- [#4418](https://github.com/emberjs/data/pull/4418) remove DEPRECATION: Using the global version of DS is deprecated when running tests
- [#4481](https://github.com/emberjs/data/pull/4481) [BUGFIX release] Revert blueprints to use the old import DS format
- [#4433](https://github.com/emberjs/data/pull/4433) Remove JSHint directives from Mocha test blueprints
- [#4435](https://github.com/emberjs/data/pull/4435) [DOC] typo fix for queryRecord (kown -> known)
- [#4431](https://github.com/emberjs/data/pull/4431) Update changelog for 2.6.1 release
- [#4454](https://github.com/emberjs/data/pull/4454) Add since tags for methods added in Ember Data 1.13
- [#4447](https://github.com/emberjs/data/pull/4447) Remove initializer methods from the API docs
- [#4446](https://github.com/emberjs/data/pull/4446) `modelHasAttributeOrRelationshipNamedType` should not show up in the API docs
- [#4444](https://github.com/emberjs/data/pull/4444) Update the API docs for the DS.Adapter class
- [#4448](https://github.com/emberjs/data/pull/4448) [BUGFIX beta] The adapter should call `ajax` instead of the new methods if it has been customized.
- [#4490](https://github.com/emberjs/data/pull/4490) [DOCS] No need to use Ember.run in success and failure of wrapped getJSON
- [#4449](https://github.com/emberjs/data/pull/4449) Add link to PR for ds-check-should-serialize-relationships feature
- [#4489](https://github.com/emberjs/data/pull/4489) [BUGFIX beta] Fix Brittle Promise Usage
- [#4470](https://github.com/emberjs/data/pull/4470) Belongs to not updating when response contains a change with the previous value
- [#4451](https://github.com/emberjs/data/pull/4451) [CLEANUP beta] Remove feature flag for ds-serialize-ids-and-types (shipped in 2.6) #4416
- [#4466](https://github.com/emberjs/data/pull/4466) [BUGFIX beta] Fixes issue with GET requests appending ?{} to url
- [#4484](https://github.com/emberjs/data/pull/4484) [BUGFIX beta] Update API docs to import DS from 'ember-data'
- [#4485](https://github.com/emberjs/data/pull/4485) Update changelog for the Ember Data 2.7.0 release
- [#4499](https://github.com/emberjs/data/pull/4499) [BUGFIX beta] add assertions for reference methods on DS.Model
- [#4503](https://github.com/emberjs/data/pull/4503) Update ember-try config to test against alpha.
- [#4515](https://github.com/emberjs/data/pull/4515) Document the allowNull property on the boolean transform
- [#4516](https://github.com/emberjs/data/pull/4516) Update the docs for normalizeModelName so they explain the intent of the function
- [#4519](https://github.com/emberjs/data/pull/4519) [BUGFIX beta] Prefer includes over contains
- [#4521](https://github.com/emberjs/data/pull/4521) Remove ContainerProxy

### Release 2.7.0 (July 25, 2016)

- [#4482](https://github.com/emberjs/data/pull/4482) Disable ds-improved-ajax for the 2.7 release
- [#4470](https://github.com/emberjs/data/pull/4470) Belongs to not updating when response contains a change with the previous value
- [#4481](https://github.com/emberjs/data/pull/4481) [BUGFIX release] Revert blueprints to use the old import DS format
- [#4484](https://github.com/emberjs/data/pull/4484) [BUGFIX beta] Update API docs to import DS from 'ember-data'
- [#4454](https://github.com/emberjs/data/pull/4454) Add since tags for methods added in Ember Data 1.13
- [#4464](https://github.com/emberjs/data/pull/4464) Add benchmarks directory to npmignore
- [#4466](https://github.com/emberjs/data/pull/4466) [BUGFIX beta] Fixes issue with GET requests appending ?{} to url
- [#4425](https://github.com/emberjs/data/pull/4425) [BUGFIX] Pass options to transform for serialization in json-api
- [#4433](https://github.com/emberjs/data/pull/4433) Remove JSHint directives from Mocha test blueprints
- [#4435](https://github.com/emberjs/data/pull/4435) [DOC] typo fix for queryRecord (kown -> known)
- [#4448](https://github.com/emberjs/data/pull/4448) [BUGFIX beta] The adapter should call `ajax` instead of the new metho…
- [#4320](https://github.com/emberjs/data/pull/4320) Fixup feature flagging infrastructure.
- [#4311](https://github.com/emberjs/data/pull/4311) Use property lookup in applyTransforms
- [#4318](https://github.com/emberjs/data/pull/4318) [FEATURE ds-payload-hooks] Add hooks to map type in payload to modelName
- [#4378](https://github.com/emberjs/data/pull/4378) [DOC] Add link to PR's for every feature
- [#4327](https://github.com/emberjs/data/pull/4327) [DOC] Update CONTRIBUTING.md for feature flags
- [#4389](https://github.com/emberjs/data/pull/4389) call super in addon#init
- [#4337](https://github.com/emberjs/data/pull/4337) [DOC] Update README.md for improve ES6 syntax in example
- [#4348](https://github.com/emberjs/data/pull/4348) [CLEANUP ds-finder-include]
- [#4347](https://github.com/emberjs/data/pull/4347) [CLEANUP ds-references]
- [#4345](https://github.com/emberjs/data/pull/4345) [DOC] fix example syntax
- [#4334](https://github.com/emberjs/data/pull/4334) Port the 2.5.x changelog entires to master
- [#4393](https://github.com/emberjs/data/pull/4393) During normalization, use property lookup instead of hasOwnProp checks
- [#4363](https://github.com/emberjs/data/pull/4363) [DOC] Fix hard-coded "Customizing Adapters" link
- [#4350](https://github.com/emberjs/data/pull/4350) [CLEANUP ds-transform-pass-options]
- [#4374](https://github.com/emberjs/data/pull/4374) Fix #4366: EmbeddedRecordsMixin embeds the record, not the snapshot
- [#4392](https://github.com/emberjs/data/pull/4392) Fix lint errors caused by merging an older pr
- [#4396](https://github.com/emberjs/data/pull/4396) Deprecate date parse
- [#4398](https://github.com/emberjs/data/pull/4398) [FEATURE ds-overhaul-references] Fix inconsistencies with Reference#push
- [#4399](https://github.com/emberjs/data/pull/4399) Add link to PR of ds-payload-type-hooks feature
- [#4403](https://github.com/emberjs/data/pull/4403) [BUGFIX beta] Correctly coalesce URI encoded ids
- [#4405](https://github.com/emberjs/data/pull/4405) [BUGFIX beta] Document the adapterOptions property
- [#4427](https://github.com/emberjs/data/pull/4427) Update changelog for the 2.6.0 release

### Release 2.6.1 (June 15, 2016)

- [#4425](https://github.com/emberjs/data/pull/4425) [BUGFIX] Pass options to transform for serialization in json-api
- [#4389](https://github.com/emberjs/data/pull/4389) call super in addon#init

### Release 2.6.0 (June 8, 2016)

- [#4386](https://github.com/emberjs/data/pull/4386) [BUGFIX release] `isUpdating` flag is set correctly for `store.findAll`
- [#4374](https://github.com/emberjs/data/pull/4374) Fix #4366: EmbeddedRecordsMixin embeds the record, not the snapshot
- [#4379](https://github.com/emberjs/data/pull/4379) [BUGFIX beta] Fix resetting of properties to in-flight values
- [#4380](https://github.com/emberjs/data/pull/4380) [BUGFIX beta] remove trailing whitespace from model blueprint
- [#4300](https://github.com/emberjs/data/pull/4300) [BUGFIX beta] Overhaul queryRecord
- [#4363](https://github.com/emberjs/data/pull/4363) [DOC] Fix hard-coded "Customizing Adapters" link
- [#4320](https://github.com/emberjs/data/pull/4320) Fixup feature flagging infrastructure.
- [#4324](https://github.com/emberjs/data/pull/4324) [DOC beta] Clarify DS.Model#changedAttributes()
- [#4324](https://github.com/emberjs/data/pull/4324) [DOC beta] Clarify DS.Model#changedAttributes()
- [#4327](https://github.com/emberjs/data/pull/4327) [DOC] Update CONTRIBUTING.md for feature flags
- [#4328](https://github.com/emberjs/data/pull/4328) [BUGFIX release] Only setup babel options once.
- [#4330](https://github.com/emberjs/data/pull/4330) [DOC beta] Make clear where `blog` is coming from
- [#4331](https://github.com/emberjs/data/pull/4331) [BUGFIX beta] Overhaul attr/relationships imports in model blueprint
- [#4338](https://github.com/emberjs/data/pull/4338) [DOC beta] Overhaul documentation for reload / background reload
- [#4345](https://github.com/emberjs/data/pull/4345) [DOC] fix example syntax
- [#4184](https://github.com/emberjs/data/pull/4184) blueprints: Use project.dependencies() to determine test framework
- [#3848](https://github.com/emberjs/data/pull/3848) [BUGFIX] EmbeddedRecordMixin should include the type serializing hasMany as ids
- [#4154](https://github.com/emberjs/data/pull/4154) Make sure new record are not pushed twice when parent is saved before.
- [#4023](https://github.com/emberjs/data/pull/4023) Enhance blueprints: only extend from application entity if it exists
- [#4177](https://github.com/emberjs/data/pull/4177) Elaborate on running tests in browser
- [#3586](https://github.com/emberjs/data/pull/3586) [FEATURE ds-extended-errors] Make adapter error extendable and add more error types
- [#3099](https://github.com/emberjs/data/pull/3099) [FEATURE ds-improved-ajax] Finer control over customizing a request
- [#4022](https://github.com/emberjs/data/pull/4022) [FEATURE ds-boolean-transform-allow-null] allow null for boolean
- [#4173](https://github.com/emberjs/data/pull/4173) Create RELEASE.md
- [#4178](https://github.com/emberjs/data/pull/4178) DS.Store type presence checks
- [#3559](https://github.com/emberjs/data/pull/3559) [BUGFIX release] Guard against isDestroyed in ManyArray.flushCanonical
- [#4259](https://github.com/emberjs/data/pull/4259) Warn when the JSONAPISerializer is extended with the EmbeddedRecordsM…
- [#4200](https://github.com/emberjs/data/pull/4200) Avoid errors when ember-cli-shims is not included.
- [#4188](https://github.com/emberjs/data/pull/4188) Update ember-cli to v2.3.0
- [#4191](https://github.com/emberjs/data/pull/4191) Don't resolve model name unless actually needed
- [#4189](https://github.com/emberjs/data/pull/4189) AppVeyor: Use same line endings as original files
- [#4193](https://github.com/emberjs/data/pull/4193) support 1.13 officially
- [#4194](https://github.com/emberjs/data/pull/4194) Use modelNameFromPayloadKey when type is given
- [#4196](https://github.com/emberjs/data/pull/4196) Restructure and elaborate on test which fixes a tricky bug
- [#4187](https://github.com/emberjs/data/pull/4187) Add acceptance tests for the mocha blueprints
- [#4197](https://github.com/emberjs/data/pull/4197) Update changelog for Ember Data 2.4
- [#4274](https://github.com/emberjs/data/pull/4274) [DOC canary] Update extractMeta documentation
- [#4230](https://github.com/emberjs/data/pull/4230) Only show ember-cli-shims errors if actually installed
- [#4214](https://github.com/emberjs/data/pull/4214) Fix AMD dependencies
- [#4223](https://github.com/emberjs/data/pull/4223) Run tests in production
- [#4205](https://github.com/emberjs/data/pull/4205) [BUGFIX release] ensure import paths are resolved \w posix separators
- [#4215](https://github.com/emberjs/data/pull/4215) unify prod/dev add-on build
- [#4225](https://github.com/emberjs/data/pull/4225) Don't do inverse work if inverse is explicitly turned off
- [#4228](https://github.com/emberjs/data/pull/4228) Solves #4186 and fixes `this._super` call within `normalize` method.
- [#4222](https://github.com/emberjs/data/pull/4222) Strip code for DS_WARN_ON_UNKNOWN_KEYS warning in production
- [#4220](https://github.com/emberjs/data/pull/4220) Use single quotes
- [#4204](https://github.com/emberjs/data/pull/4204) Fix RESTAdapter.findRecord without a snapshot
- [#4264](https://github.com/emberjs/data/pull/4264) Moved the adapter errors into the public API space.
- [#4247](https://github.com/emberjs/data/pull/4247) Add test asserting no unnecessary inverse work
- [#4235](https://github.com/emberjs/data/pull/4235) [DOC] Fix store.findAll return type
- [#4243](https://github.com/emberjs/data/pull/4243) moves the ember dep in the package-manager package.json into optionalDependencies
- [#4241](https://github.com/emberjs/data/pull/4241) Fix spacing issue thats causing jscs errors on the beta branch
- [#4240](https://github.com/emberjs/data/pull/4240) Add note on `testInDebug`
- [#4248](https://github.com/emberjs/data/pull/4248) fix prod-build issue
- [#4244](https://github.com/emberjs/data/pull/4244) [DOC] Add section on commit tagging to CONTRIBUTING.md
- [#4245](https://github.com/emberjs/data/pull/4245) Tweaks to docs on error responses
- [#4287](https://github.com/emberjs/data/pull/4287) [FEATURE ds-extended-errors] add DS.ServerError
- [#4270](https://github.com/emberjs/data/pull/4270) Fix incorrect reference to `push` in the `findRecord` docs
- [#4260](https://github.com/emberjs/data/pull/4260) Modified the setup-ember-dev test helper to use `ember-metal/debug`s override hooks
- [#4263](https://github.com/emberjs/data/pull/4263) [FEATURE ds-links-in-record-array] Add links to RecordArray when present on payload
- [#4257](https://github.com/emberjs/data/pull/4257) Update changelog for Ember Data 2.4.3
- [#4268](https://github.com/emberjs/data/pull/4268) JSONSerializer should normalize the links object using the attrs hash
- [#4258](https://github.com/emberjs/data/pull/4258) Deprecate normalizeHash method on the rest serializer
- [#4301](https://github.com/emberjs/data/pull/4301) fix rest-adapter-test typo
- [#4278](https://github.com/emberjs/data/pull/4278) Uses bin/start with friendly error message for npm start.
- [#4276](https://github.com/emberjs/data/pull/4276) [BUGFIX canary] Improve finders assertion messages
- [#4304](https://github.com/emberjs/data/pull/4304) pass DS.SnapshotRecordArray to build-url-mixin buildURL
- [#4280](https://github.com/emberjs/data/pull/4280) Update "blueprint-test-helpers" and "ember-cli"
- [#4307](https://github.com/emberjs/data/pull/4307) [skip ci] fix invalid indentation in codeclimate.yml
- [#4288](https://github.com/emberjs/data/pull/4288) [FEATURE ds-extended-errors] fix usage of isEnabled
- [#4284](https://github.com/emberjs/data/pull/4284) [CLEANUP] Use Array.isArray everywhere instead of Ember.isArray
- [#4281](https://github.com/emberjs/data/pull/4281) Speed up JSONSerializer#applyTransforms
- [#4286](https://github.com/emberjs/data/pull/4286) Use the dot reporter to reduce the noise in travis output
- [#4308](https://github.com/emberjs/data/pull/4308) pass snapshot through to urlForFindHasMany and urlForFindBelongsTo
- [#4316](https://github.com/emberjs/data/pull/4316) Fix `isUpdating` for DS.AdapterPopulatedRecordArray#update()
- [#4317](https://github.com/emberjs/data/pull/4317) [CLEANUP] remove reference to no more used isNewSerializerAPI flag

### Release 2.5.3 (May 17, 2016)

- [#4386](https://github.com/emberjs/data/pull/4386) [BUGFIX release] `isUpdating` flag is set correctly for `store.findAll`

### Release 2.5.2 (April 14, 2016)

- [#4328](https://github.com/emberjs/data/pull/4328) [BUGFIX release] Only setup babel options once.
- [#4333](https://github.com/emberjs/data/pull/4333) [BUGFIX release] use es5 syntax for addon's index.js file

### Release 2.5.1 (April 12, 2016)

- [#4320](https://github.com/emberjs/data/pull/4320) [BUGFIX release] Ensure feature flag stripping works for all builds.

### Release 2.5.0 (April 11, 2016)

- [#4293](https://github.com/emberjs/data/pull/4293) Transition an invalid created record to the deleted saved state when deleted
- [#4304](https://github.com/emberjs/data/pull/4304) pass DS.SnapshotRecordArray to build-url-mixin buildURL
- [#4308](https://github.com/emberjs/data/pull/4308) pass snapshot through to urlForFindHasMany and urlForFindBelongsTo
- [#4314](https://github.com/emberjs/data/pull/4314) [BUGFIX beta] convert single record sideloaded records to plural
- [#4316](https://github.com/emberjs/data/pull/4316) Fix `isUpdating` for DS.AdapterPopulatedRecordArray#update()
- [#4245](https://github.com/emberjs/data/pull/4245) Tweaks to docs on error responses
- [#4268](https://github.com/emberjs/data/pull/4268) JSONSerializer should normalize the links object using the attrs hash
- [#4270](https://github.com/emberjs/data/pull/4270) Fix incorrect reference to `push` in the `findRecord` docs
- [#4271](https://github.com/emberjs/data/pull/4271) [BUGFIX beta] Ensure `null` is returned for Reference#value()
- [#4274](https://github.com/emberjs/data/pull/4274) [DOC canary] Update extractMeta documentation
- [#4295](https://github.com/emberjs/data/pull/4295) [DOC release] Mistaken back tick.
- [#4178](https://github.com/emberjs/data/pull/4178) DS.Store type presence checks
- [#4194](https://github.com/emberjs/data/pull/4194) Use modelNameFromPayloadKey when type is given
- [#4243](https://github.com/emberjs/data/pull/4243) moves the ember dep in the package-manager package.json into optionalDependencies
- [#4248](https://github.com/emberjs/data/pull/4248) fix prod-build issue
- [#4250](https://github.com/emberjs/data/pull/4250) [BUGFIX beta] Use Ember.assign when availability
- [#4256](https://github.com/emberjs/data/pull/4256) [BUGFIX release] Revert pr #3864
- [#4214](https://github.com/emberjs/data/pull/4214) Fix AMD dependencies
- [#4184](https://github.com/emberjs/data/pull/4184) blueprints: Use project.dependencies() to determine test framework
- [#3559](https://github.com/emberjs/data/pull/3559) [BUGFIX release] Guard against isDestroyed in ManyArray.flushCanonical
- [#4154](https://github.com/emberjs/data/pull/4154) Make sure new record are not pushed twice when parent is saved before.
- [#4198](https://github.com/emberjs/data/pull/4198) [DOC beta] Fix error message internal docs
- [#4200](https://github.com/emberjs/data/pull/4200) Avoid errors when ember-cli-shims is not included.
- [#4204](https://github.com/emberjs/data/pull/4204) Fix RESTAdapter.findRecord without a snapshot
- [#4205](https://github.com/emberjs/data/pull/4205) [BUGFIX release] ensure import paths are resolved \w posix separators
- [#4221](https://github.com/emberjs/data/pull/4221) [BUGFIX beta] use assert from debug utils so it is stripped correctly
- [#4235](https://github.com/emberjs/data/pull/4235) [DOC] Fix store.findAll return type
- [#4237](https://github.com/emberjs/data/pull/4237) [DOC beta] Fix typo in inline doc. of normalizeResponse
- [#4119](https://github.com/emberjs/data/pull/4119) Add ember.js and ember-data tags automatically to SO question
- [#4063](https://github.com/emberjs/data/pull/4063) [BUGFIX release] don't load "app" code when loading globals files
- [#4040](https://github.com/emberjs/data/pull/4040) Use test helpers from ember dev
- [#4116](https://github.com/emberjs/data/pull/4116) Add assertions for store#query()
- [#4066](https://github.com/emberjs/data/pull/4066) Use correct version number when used as an addon.
- [#4065](https://github.com/emberjs/data/pull/4065) Bump canary to 2.5.0
- [#4070](https://github.com/emberjs/data/pull/4070) Update blueprints to import modules directly
- [#4111](https://github.com/emberjs/data/pull/4111) [BUGFIX beta] Add ducktyping of `AdapterError`
- [#4084](https://github.com/emberjs/data/pull/4084) [cleanup] Remove unnecessary inline JSHint config
- [#4082](https://github.com/emberjs/data/pull/4082) Move the date import to where it is used intead of the root module
- [#4074](https://github.com/emberjs/data/pull/4074) Update README, now that ember-data is a proper addon
- [#4079](https://github.com/emberjs/data/pull/4079) [CLEANUP] remove unused config/ember-defeatureify.js
- [#4078](https://github.com/emberjs/data/pull/4078) Use `Ember.merge` instead of ember-data's shim
- [#4090](https://github.com/emberjs/data/pull/4090) Make yui doc generate links from the project root instead of the file…
- [#4085](https://github.com/emberjs/data/pull/4085) Update codeclimate.yml
- [#4086](https://github.com/emberjs/data/pull/4086) [FEATURE ds-transform-pass-options] pass options to DS.Transform
- [#4141](https://github.com/emberjs/data/pull/4141) [DOC] Document behavior of object level errors with JSON API
- [#4094](https://github.com/emberjs/data/pull/4094) Update changelog for 2.3.2 release
- [#4092](https://github.com/emberjs/data/pull/4092) Delete TRANSITION.md
- [#4152](https://github.com/emberjs/data/pull/4152) Remove extra definition of InvalidError
- [#4100](https://github.com/emberjs/data/pull/4100) [DOC] Replace reference to DS.Store.find
- [#4102](https://github.com/emberjs/data/pull/4102) [DOC] Fix misleading docs for `DS.RESTAdapter.findBelongsTo`
- [#4110](https://github.com/emberjs/data/pull/4110) [FEATURE ds-pushpayload-return] Change `pushPayload` to return a value.
- [#4097](https://github.com/emberjs/data/pull/4097) Update `.npmignore`
- [#4104](https://github.com/emberjs/data/pull/4104) [DOC] Mark `DS.Store.filter` as private
- [#4101](https://github.com/emberjs/data/pull/4101) [cleanup] Remove unneeded `getComputedPropertyDesc` test helper
- [#4160](https://github.com/emberjs/data/pull/4160) Fixes broken link
- [#4128](https://github.com/emberjs/data/pull/4128) Fix calls to keyForRelationship in embedded records
- [#4117](https://github.com/emberjs/data/pull/4117) Add assertion for polymorphic type for HasManyReference#push
- [#4118](https://github.com/emberjs/data/pull/4118) [ci skip] Sort CHANGELOG by version and not date of release
- [#4164](https://github.com/emberjs/data/pull/4164) [CLEANUP] remove `toString` definitions for models in tests
- [#4147](https://github.com/emberjs/data/pull/4147) Fix key remapping for embedded belongsTo
- [#4135](https://github.com/emberjs/data/pull/4135) import require
- [#4153](https://github.com/emberjs/data/pull/4153) calling reload multiple times on a has many triggers only one request
- [#4155](https://github.com/emberjs/data/pull/4155) remove container related deprecation warnings
- [#4159](https://github.com/emberjs/data/pull/4159) [DOC] Mark store.filter as deprecated in JSDoc.
- [#4167](https://github.com/emberjs/data/pull/4167) Add blueprints from ember-cli-mocha
- [#4168](https://github.com/emberjs/data/pull/4168) TravisCI: Use PhantomJS v2.1.1
- [#4169](https://github.com/emberjs/data/pull/4169) Simplify PhantomJS installation on TravisCI
- [#4171](https://github.com/emberjs/data/pull/4171) [CLEANUP] Remove shim for Backburner.join
- [#4172](https://github.com/emberjs/data/pull/4172) [CLEANUP] Remove shim for Ember.Service
- [#4224](https://github.com/emberjs/data/pull/4224) Enable feature flags for 2.5 beta cycle

### Release 2.4.3 (March 22, 2016)

- [#4243](https://github.com/emberjs/data/pull/4243) moves the ember dep in the package-manager package.json into optionalDependencies
- [#4256](https://github.com/emberjs/data/pull/4256) [BUGFIX release] Revert pr #3864

### Release 2.4.2 (March 19, 2016)

- [#4248](https://github.com/emberjs/data/pull/4248) [BUGFIX release] fix prod-build issue

### Release 2.4.1 (March 18, 2016)

- [#3559](https://github.com/emberjs/data/pull/3559) [BUGFIX release] Guard against isDestroyed in ManyArray.flushCanonical
- [#4154](https://github.com/emberjs/data/pull/4154) Make sure new record are not pushed twice when parent is saved before.
- [#4204](https://github.com/emberjs/data/pull/4204) Fix RESTAdapter.findRecord without a snapshot
- [#4205](https://github.com/emberjs/data/pull/4205) [BUGFIX release] ensure import paths are resolved \w posix separators
- [#4214](https://github.com/emberjs/data/pull/4214) Fix AMD dependencies

### Release 2.4.0 (February 29, 2016)

- [#4125](https://github.com/emberjs/data/pull/4125) [BUGFIX beta] Export more public API's via modules
- [#4135](https://github.com/emberjs/data/pull/4135) import require
- [#4137](https://github.com/emberjs/data/pull/4137) [BUGFIX beta] Allow optional spaces when parsing response headers
- [#4141](https://github.com/emberjs/data/pull/4141) [DOC] Document behavior of object level errors with JSON API
- [#4147](https://github.com/emberjs/data/pull/4147) Fix key remapping for embedded belongsTo
- [#4167](https://github.com/emberjs/data/pull/4167) Add blueprints from ember-cli-mocha
- [#4082](https://github.com/emberjs/data/pull/4082) Move the date import to where it is used intead of the root module
- [#4063](https://github.com/emberjs/data/pull/4063) [BUGFIX release] don't load "app" code when loading globals files
- [#4088](https://github.com/emberjs/data/pull/4088) [BUFGIX release] Fix regression with missing initializers
- [#4066](https://github.com/emberjs/data/pull/4066) Use correct version number when used as an addon.
- [#4072](https://github.com/emberjs/data/pull/4072) [BUGFIX release] Fix bundled source path for gem
- [#4073](https://github.com/emberjs/data/pull/4073) [BUGFIX release] Add missing dist source to gem
- [#4077](https://github.com/emberjs/data/pull/4077) [CLEANUP beta] Change the way metadata in response is stored on record array
- [#4084](https://github.com/emberjs/data/pull/4084) [cleanup] Remove unnecessary inline JSHint config
- [#4090](https://github.com/emberjs/data/pull/4090) Make yui doc generate links from the project root instead of the file…
- [#4091](https://github.com/emberjs/data/pull/4091) [BUGFIX release] Refactor Model.reopen to use mixins
- [#4095](https://github.com/emberjs/data/pull/4095) [BUGFIX release] Remove 'v' prefix from `DS.VERSION`
- [#4108](https://github.com/emberjs/data/pull/4108) [BUGFIX beta] Fix `BuildUrlMixin.urlPrefix` regression when host=/
- [#3999](https://github.com/emberjs/data/pull/3999) Run the Ember Data initializer when Ember Data is loaded as an Ember …
- [#3941](https://github.com/emberjs/data/pull/3941) Mark `adapterFor` and `serializerFor` as public
- [#3813](https://github.com/emberjs/data/pull/3813) ember-data should provide its blueprints
- [#3916](https://github.com/emberjs/data/pull/3916) `Store._find` asserts `adapterPayload` not empty
- [#3940](https://github.com/emberjs/data/pull/3940) Remove JSONSerializer#normalizeId
- [#3303](https://github.com/emberjs/data/pull/3303) Implement RFC 57 - Reference Unification
- [#3864](https://github.com/emberjs/data/pull/3864) Throw a more helpful error message if the response from queryRecord i…
- [#3930](https://github.com/emberjs/data/pull/3930) Friendly Errors
- [#2384](https://github.com/emberjs/data/pull/2384) Directly reloading a hasMany with links should trigger only one request
- [#3853](https://github.com/emberjs/data/pull/3853) fix transitioning into invalid state
- [#3841](https://github.com/emberjs/data/pull/3841) Log a deprecation warning when when Ember Data is loaded with Ember 1.13
- [#3926](https://github.com/emberjs/data/pull/3926) Run `ember watson: methodify` on `addon/` and `test/`
- [#4009](https://github.com/emberjs/data/pull/4009) [FEATURE ds-references] More conistency for RecordReference
- [#3961](https://github.com/emberjs/data/pull/3961) Add a better error message when findRecord returns an array
- [#3949](https://github.com/emberjs/data/pull/3949) Fix incorrect reference in store api docs
- [#3946](https://github.com/emberjs/data/pull/3946) Report better error when `type` is missing from a JSONApi response
- [#3958](https://github.com/emberjs/data/pull/3958) [DOCS fix] fix incorrect argument description...
- [#4014](https://github.com/emberjs/data/pull/4014) Register the version before the DEBUG version are printed when loadin…
- [#3968](https://github.com/emberjs/data/pull/3968) Add failing test on PromiseArray.createRecord when called before hasM…
- [#3965](https://github.com/emberjs/data/pull/3965) [Doc] Specify the status code expected to populate the error object
- [#3964](https://github.com/emberjs/data/pull/3964) Merge normalizeRelationships and setupRelationships methods in store
- [#3967](https://github.com/emberjs/data/pull/3967) Added documentation to modify the hash by reference
- [#3966](https://github.com/emberjs/data/pull/3966) tests for #3707
- [#4016](https://github.com/emberjs/data/pull/4016) Add missing dependencies for the changelog script
- [#3970](https://github.com/emberjs/data/pull/3970) [CLEANUP] move test file to correct location
- [#4017](https://github.com/emberjs/data/pull/4017) [FEATURE ds-references] bring back accidentally removed tests
- [#3985](https://github.com/emberjs/data/pull/3985) Remove extraneous conditional in ajax()
- [#3980](https://github.com/emberjs/data/pull/3980) Add license field to bower.json
- [#3979](https://github.com/emberjs/data/pull/3979) Re-enable feature flags
- [#3974](https://github.com/emberjs/data/pull/3974) Remove duplicate createRecord test
- [#3973](https://github.com/emberjs/data/pull/3973) [CLEANUP] use debug helpers from ember-data/debug
- [#3983](https://github.com/emberjs/data/pull/3983) Fix documentation to use "serializedHasManyName"
- [#3984](https://github.com/emberjs/data/pull/3984) Cleanup .jshintrc since no globals are used anymore
- [#3976](https://github.com/emberjs/data/pull/3976) Allow `include` query parameter with store.findRecord & store.findAll
- [#4000](https://github.com/emberjs/data/pull/4000) Re-enable pushing builds to S3
- [#3996](https://github.com/emberjs/data/pull/3996) Update ember-cli-shims to 0.1.0 to silence ED's own warning
- [#3988](https://github.com/emberjs/data/pull/3988) [PERF] Don't use array methods
- [#3989](https://github.com/emberjs/data/pull/3989) Rely on internalModel.createSnapshot to set adapterOptions
- [#3990](https://github.com/emberjs/data/pull/3990) Update adapter function references in test
- [#3993](https://github.com/emberjs/data/pull/3993) Do not publish .gem files to npm
- [#4025](https://github.com/emberjs/data/pull/4025) Use keyForReliationship for belongsTo and hasMany
- [#4007](https://github.com/emberjs/data/pull/4007) [CLEANUP] Use `isEnabled` instead of `Ember.FEATURES` directly
- [#4006](https://github.com/emberjs/data/pull/4006) [CLEANUP] Separate buildURL tests from pathForType tests
- [#4001](https://github.com/emberjs/data/pull/4001) Add ember-publisher to package.json
- [#4004](https://github.com/emberjs/data/pull/4004) [CLEANUP] remove unused feature-flags.js
- [#4003](https://github.com/emberjs/data/pull/4003) Only run the Ember.onload initializers in globals mode
- [#4005](https://github.com/emberjs/data/pull/4005) don't cache length in for loops
- [#4002](https://github.com/emberjs/data/pull/4002) Fix paths to files which should be uploaded to S3
- [#4049](https://github.com/emberjs/data/pull/4049) Run node tests and optional feature tests on AppVeyor
- [#4015](https://github.com/emberjs/data/pull/4015) [CLEANUP] Don't cache length in for loops
- [#4019](https://github.com/emberjs/data/pull/4019) Use JSON-API adapter and serializer in blueprints
- [#4018](https://github.com/emberjs/data/pull/4018) [CLEANUP] re-use test setup to assert correct call to adapter.ajax
- [#4011](https://github.com/emberjs/data/pull/4011) [CLEANUP] Update and remove obsolete comments
- [#4030](https://github.com/emberjs/data/pull/4030) [CLEANUP] use methods from utils module directly
- [#4029](https://github.com/emberjs/data/pull/4029) Move public modules out of the `-private` folder
- [#4051](https://github.com/emberjs/data/pull/4051) Make setup-container public to allow consuming apps more flexibility with initializer
- [#4037](https://github.com/emberjs/data/pull/4037) Happy New Year!
- [#4035](https://github.com/emberjs/data/pull/4035) Simplify the urlPrefix method to make it easier to understand
- [#4031](https://github.com/emberjs/data/pull/4031) [CLEANUP] Remove special logic for meta.descs in tests
- [#4032](https://github.com/emberjs/data/pull/4032) [CLEANUP] remove obsolete code within Store#willDestroy
- [#4039](https://github.com/emberjs/data/pull/4039) Replace calls to store.find with store.findRecord
- [#4053](https://github.com/emberjs/data/pull/4053) [FEATURE ds-references] Only add function to prototype if enabled
- [#4059](https://github.com/emberjs/data/pull/4059) Update name for feature in FEATURES.md

### Release 2.3.3 (January 21, 2016)

- [#4095](https://github.com/emberjs/data/pull/4095) [BUGFIX release] Remove 'v' prefix from `DS.VERSION`

### Release 2.3.2 (January 18, 2016)

- [#4000](https://github.com/emberjs/data/pull/4000) Re-enable pushing builds to S3
- [#4002](https://github.com/emberjs/data/pull/4002) Fix paths to files which should be uploaded to S3
- [#4072](https://github.com/emberjs/data/pull/4072) [BUGFIX release] Fix bundled source path for gem
- [#4073](https://github.com/emberjs/data/pull/4073) [BUGFIX release] Add missing dist source to gem
- [#4082](https://github.com/emberjs/data/pull/4082) Move the date import to where it is used intead of the root module
- [#4084](https://github.com/emberjs/data/pull/4084) [cleanup] Remove unnecessary inline JSHint config
- [#4088](https://github.com/emberjs/data/pull/4088) [BUFGIX release] Fix regression with missing initializers
- [#4090](https://github.com/emberjs/data/pull/4090) Make yui doc generate links from the project root instead of the file…
- [#4091](https://github.com/emberjs/data/pull/4091) [BUGFIX release] Refactor Model.reopen to use mixins

### Release 2.3.1 (January 12, 2016)

- [#4063](https://github.com/emberjs/data/pull/4063) [BUGFIX release] don't load "app" code when loading globals files
- [#4066](https://github.com/emberjs/data/pull/4066) Use correct version number when used as an addon.

### Release 2.3.0 (January 12, 2016)

Ember Data 2.3 is now published as and Ember CLI addon in addition to a bower package.
See the [release notes](https://emberjs.com/blog/2016/01/12/ember-data-2-3-released.html#toc_changes-in-ember-data-2-3)
for instruction on how to upgrade your Ember CLI project to take advantage of the Ember Data addon.

- [#4039](https://github.com/emberjs/data/pull/4039) Replace calls to store.find with store.findRecord
- [#4042](https://github.com/emberjs/data/pull/4042) [BUGFIX beta] prevent calls to store.query leaking
- [#4048](https://github.com/emberjs/data/pull/4048) Strip stuff from addon before it is added to app
- [#4050](https://github.com/emberjs/data/pull/4050) [BUGFIX beta] Functional update for adapter populated record arrays
- [#4051](https://github.com/emberjs/data/pull/4051) Make setup-container public to allow consuming apps more flexibility with initializer
- [#4052](https://github.com/emberjs/data/pull/4052) [DOC beta] Hide private classes from YUIDoc
- [#4055](https://github.com/emberjs/data/pull/4055) [BUGFIX beta] pin jquery to 1.11.3 to fix broken build
- [#4057](https://github.com/emberjs/data/pull/4057) [BUGFIX beta] fail builds in ember-cli when ember-cli-shims isn't met
- [#4058](https://github.com/emberjs/data/pull/4058) [BUGFIX beta] Do not expose the array argument on store.query
- [#4060](https://github.com/emberjs/data/pull/4060) Require ember-source 2.x
- [#4018](https://github.com/emberjs/data/pull/4018) [CLEANUP] re-use test setup to assert correct call to adapter.ajax
- [#4019](https://github.com/emberjs/data/pull/4019) Use JSON-API adapter and serializer in blueprints
- [#4021](https://github.com/emberjs/data/pull/4021) [BUGFIX beta] Move ember-inflector to an explicit dependency for the …
- [#4025](https://github.com/emberjs/data/pull/4025) Use keyForReliationship for belongsTo and hasMany
- [#4029](https://github.com/emberjs/data/pull/4029) [BUGFIX beta] Move public modules out of the `-private` folder
- [#4026](https://github.com/emberjs/data/pull/4026) [BUGFIX beta] ignores keys that are not found in the map
- [#3813](https://github.com/emberjs/data/pull/3813) ember-data should provide its blueprints
- [#3996](https://github.com/emberjs/data/pull/3996) Update ember-cli-shims to 0.1.0 to silence ED's own warning
- [#3999](https://github.com/emberjs/data/pull/3999) Run the Ember Data initializer when Ember Data is loaded as an Ember …
- [#4003](https://github.com/emberjs/data/pull/4003) Only run the Ember.onload initializers in globals mode
- [#4010](https://github.com/emberjs/data/pull/4010) [DOC beta] Mark comments as private
- [#4014](https://github.com/emberjs/data/pull/4014) Register the version before the DEBUG version are printed when loadin…
- [#3995](https://github.com/emberjs/data/pull/3995) [BUGFIX beta] Implement public module API.
- [#3865](https://github.com/emberjs/data/pull/3943) [PERF] Ajax should join an existing run if one exists
- [#3949](https://github.com/emberjs/data/pull/3949) Fix incorrect reference in store api docs
- [#3841](https://github.com/emberjs/data/pull/3841) Log a deprecation warning when when Ember Data is loaded with Ember 1.13
- [#3973](https://github.com/emberjs/data/pull/3973) [CLEANUP] use debug helpers from ember-data/debug
- [#3978](https://github.com/emberjs/data/pull/3978) [BUGFIX beta] bump ember-inflector
- [#3983](https://github.com/emberjs/data/pull/3983) [DOC beta] Fix documentation to use "serializedHasManyName"
- [#3986](https://github.com/emberjs/data/pull/3986) Move private modules into the `-private` directory
- [#3865](https://github.com/emberjs/data/pull/3865) Assert that passed array to set a hasMany consists of records
- [#3820](https://github.com/emberjs/data/pull/3820) [CLEANUP] Remove duplicate test for creating record
- [#3819](https://github.com/emberjs/data/pull/3819) [CLEANUP] Remove duplicate `default export` in snapshot.js
- [#3713](https://github.com/emberjs/data/pull/3713) Document the return value of DS.Adapter#updateRecord
- [#3390](https://github.com/emberjs/data/pull/3390) Update the jsbin link so it has no deprecation warnings
- [#3835](https://github.com/emberjs/data/pull/3835) [BUGFIX] extract polymorphic belongsTo in RESTSerializer
- [#3829](https://github.com/emberjs/data/pull/3829) Remove references to findQuery
- [#3824](https://github.com/emberjs/data/pull/3824) [DOCS] Improve docs for JSONSerializer
- [#3828](https://github.com/emberjs/data/pull/3828) [CLEANUP] Make idiomatic use of `export default`
- [#3821](https://github.com/emberjs/data/pull/3821) [CLEANUP] Remove unecessary wrap of rejection in run-loop
- [#3827](https://github.com/emberjs/data/pull/3827) [DOC] Remove reference to `isDirty` in DS.Model documentation
- [#3839](https://github.com/emberjs/data/pull/3839) Cleanup build
- [#3831](https://github.com/emberjs/data/pull/3831) [CLEANUP] dasherize file name for hasRecordForId test
- [#3830](https://github.com/emberjs/data/pull/3830) Fix tests for non-dasherized lookups
- [#3837](https://github.com/emberjs/data/pull/3837) [BUGFIX] Attribute/relationship named "type" of embedded record is considered before normalization
- [#3832](https://github.com/emberjs/data/pull/3832) Fix API docs for JSONAPISerializer.normalize
- [#3834](https://github.com/emberjs/data/pull/3834) raise errors on deprecation
- [#3843](https://github.com/emberjs/data/pull/3843) Remove unneeded PromiseArray allocation
- [#3844](https://github.com/emberjs/data/pull/3844) Remove conditional statement that is always true
- [#3855](https://github.com/emberjs/data/pull/3855) Deprecate complex objects as an attributes `defaultValue`.
- [#3850](https://github.com/emberjs/data/pull/3850) [DOC] Document snapshotRecordArray param passed to adapter.findAll
- [#3868](https://github.com/emberjs/data/pull/3868) Reset changed attributes when matching data is pushed
- [#3869](https://github.com/emberjs/data/pull/3869) Update the Changelog for 1.13.14
- [#3867](https://github.com/emberjs/data/pull/3867) Allow serializers to normalize response, remove old internal serializers code
- [#3858](https://github.com/emberjs/data/pull/3858) [DOC] remove documentation for `isError` in states
- [#3866](https://github.com/emberjs/data/pull/3866) Allow store.push to accept { data: null }
- [#3860](https://github.com/emberjs/data/pull/3860) [CLEANUP] remove unused private method in AdapterPopulatedRecordArray
- [#3907](https://github.com/emberjs/data/pull/3907) Addonize
- [#3898](https://github.com/emberjs/data/pull/3898) Fix DS.Errors summary and error object example
- [#3889](https://github.com/emberjs/data/pull/3889) [perf] minor adjustments to `store#push` flow
- [#3928](https://github.com/emberjs/data/pull/3928) update README stating no IE8 support
- [#3915](https://github.com/emberjs/data/pull/3915) Add null implementation of findMany in DS.Adapter
- [#3904](https://github.com/emberjs/data/pull/3904) Cleanup `.codeclimate.yml`
- [#3912](https://github.com/emberjs/data/pull/3912) Use public API for container/registry when possible.
- [#3924](https://github.com/emberjs/data/pull/3924) [CLEANUP] `tests/integration/adapter/find-test.js`
- [#3925](https://github.com/emberjs/data/pull/3925) [CLEANUP] Clean up adapter/find-all-test.js
- [#3927](https://github.com/emberjs/data/pull/3927) restore globals publishing to canary build
- [#3929](https://github.com/emberjs/data/pull/3929) upgrade node to 4 on CI
- [#3931](https://github.com/emberjs/data/pull/3931) update ember-cli to 1.13.12

### Release 2.2.0 (November 17, 2015)

- [#3937](https://github.com/emberjs/data/pull/3937) [BUGFIX beta] Warn instead of asserting when a mapped key doesn't mat…
- [#3868](https://github.com/emberjs/data/pull/3868) Reset changed attributes when matching data is pushed
- [#3875](https://github.com/emberjs/data/pull/3875) [BUGFIX beta] serialize type for embedded, polymorphic belongsTo
- [#3900](https://github.com/emberjs/data/pull/3900) [DOC fix] errors pointers should start with a /
- [#3905](https://github.com/emberjs/data/pull/3905) [BUGFIX release] Update the dependencies for Ember 2.x
- [#3909](https://github.com/emberjs/data/pull/3909) [BUGFIX beta] Correctly handle object level errors in json api
- [#3910](https://github.com/emberjs/data/pull/3910) [BUGFIX release] Normalize attrs keys
- [#3912](https://github.com/emberjs/data/pull/3912) Use public API for container/registry when possible.]
- [#3835](https://github.com/emberjs/data/pull/3835) [BUGFIX] extract polymorphic belongsTo in RESTSerializer
- [#3887](https://github.com/emberjs/data/pull/3887) [BUGFIX release] update ember-inflector to resolve default Inflector …
- [#3888](https://github.com/emberjs/data/pull/3888) [BUGFIX release] import from ember-inflector to use the default instance
- [#3832](https://github.com/emberjs/data/pull/3832) Fix API docs for JSONAPISerializer.normalize
- [#3837](https://github.com/emberjs/data/pull/3837) [BUGFIX] Attribute/relationship named "type" of embedded record is considered before normalization
- [#3846](https://github.com/emberjs/data/pull/3846) [BUGFIX beta] Attribute/relationship named "type" of primary record i…
- [#3847](https://github.com/emberjs/data/pull/3847) [BUGFIX beta] JSONAPI serializer not respecting 'attrs' hash
- [#3857](https://github.com/emberjs/data/pull/3857) [BUGFIX beta] rollbackAttributes() works after multiple failed saves
- [#3859](https://github.com/emberjs/data/pull/3859) [BUGFIX beta] Correctly handle invalid errors without payload or pointer
- [#3861](https://github.com/emberjs/data/pull/3861) [BUGFIX beta] Assert that an array is returned from the normalized re…
- [#3867](https://github.com/emberjs/data/pull/3867) Allow serializers to normalize response, remove old internal serializers code
- [#3697](https://github.com/emberjs/data/pull/3697) Fix typo in CHANGELOG
- [#3215](https://github.com/emberjs/data/pull/3215) remove Map/MapWithDefault polyfills, use Ember's ones
- [#3711](https://github.com/emberjs/data/pull/3711) Explicitly set length after setting a new content property
- [#3714](https://github.com/emberjs/data/pull/3714) Update the location of the custom store in the API doc example
- [#3699](https://github.com/emberjs/data/pull/3699) [refactor] add some tests asserting polymorphic relationships can be …
- [#3751](https://github.com/emberjs/data/pull/3751) Remove normalizePayload, associated docs, and mention of functionality.
- [#3732](https://github.com/emberjs/data/pull/3732) follow up fixes for #3701
- [#3746](https://github.com/emberjs/data/pull/3746) Improve test coverage for store#findRecord()
- [#3722](https://github.com/emberjs/data/pull/3722) Shape and cleanup
- [#3739](https://github.com/emberjs/data/pull/3739) store example should use findRecord()
- [#3734](https://github.com/emberjs/data/pull/3734) Revert "Explicitly set length after setting a new content property"
- [#3783](https://github.com/emberjs/data/pull/3783) Update changelog for 2.0.1 release
- [#3771](https://github.com/emberjs/data/pull/3771) update coalesceFindRequests doc for JSONAPIAdapter
- [#3774](https://github.com/emberjs/data/pull/3774) Fix embedded key serialization bug and refactor key serialization
- [#3773](https://github.com/emberjs/data/pull/3773) Break apart embedded serialize methods in EmbeddedRecordsMixin
- [#3777](https://github.com/emberjs/data/pull/3777) Remove unused test module
- [#3788](https://github.com/emberjs/data/pull/3788) Port pr #3725 to the release 2.0 branch
- [#3795](https://github.com/emberjs/data/pull/3795) Trigger an assertion when calling `findRecord` with falsy (except 0) id
- [#3808](https://github.com/emberjs/data/pull/3808) Update internal-model.js
- [#3814](https://github.com/emberjs/data/pull/3814) [BUGFIX] Do not deserialize when a relationship named `type` exists
- [#3816](https://github.com/emberjs/data/pull/3816) run optional feature tests on AppVeyor
- [#3817](https://github.com/emberjs/data/pull/3817) Update the changelog for Ember Data 2.1.0

### Release 2.1.0 (October 5, 2015)

- [#3811](https://github.com/emberjs/data/pull/3811) Format lists in JSONSerializer docs for rendering
- [#3814](https://github.com/emberjs/data/pull/3814) [BUGFIX] Do not deserialize when a relationship named `type` exists
- [#3781](https://github.com/emberjs/data/pull/3781) [BUGFIX beta] Fix id property in DS.Model once and for all
- [#3783](https://github.com/emberjs/data/pull/3783) Update changelog for 2.0.1 release
- [#3788](https://github.com/emberjs/data/pull/3788) Port pr #3725 to the release 2.0 branch
- [#3793](https://github.com/emberjs/data/pull/3793) Map iteration has `value, key` params 'backwards'
- [#3794](https://github.com/emberjs/data/pull/3794) [DOC release] Update documentation for store
- [#3796](https://github.com/emberjs/data/pull/3796) [DOC release] Update documentation for EmbeddedRecordsMixin.
- [#3764](https://github.com/emberjs/data/pull/3764) [BUGFIX beta] Support JSON API links object
- [15d4360c](https://github.com/emberjs/data/commit/15d4360c1be0906f594718d55660151cd5f26af3) [BUGFIX release] Improve links vs. local data for relationships
- [#3751](https://github.com/emberjs/data/pull/3751) Remove normalizePayload, associated docs, and mention of functionality.
- [#3749](https://github.com/emberjs/data/pull/3749) [DOC beta] Update Object Root docs re: plurals
- [#3763](https://github.com/emberjs/data/pull/3763) [BUGFIX beta] JSONAPISerializer warns for unknown type
- [#3767](https://github.com/emberjs/data/pull/3767) [BUGFIX release] Do not export jsdoc information for store helper fun…
- [#3771](https://github.com/emberjs/data/pull/3771) update coalesceFindRequests doc for JSONAPIAdapter
- [#3739](https://github.com/emberjs/data/pull/3739) store example should use findRecord()
- [#3747](https://github.com/emberjs/data/pull/3747) [BUGFIX beta] JSONSerializer.extractRelationships() issue #3736
- [#3779](https://github.com/emberjs/data/pull/3779) [BUGFIX release] Remove store method deprecations
- [#3778](https://github.com/emberjs/data/pull/3778) [BUGFIX release] Remove deprecation on store.filter
- [#3776](https://github.com/emberjs/data/pull/3776) [BUGFIX release] Remove deprecation for old InvalidErrors format
- [#3765](https://github.com/emberjs/data/pull/3765) [BUGFIX beta] Fix JSONSerializer.serializeHasMany() issue #3760
- [#3782](https://github.com/emberjs/data/pull/3782) [DOC release] Remove private label for findAll, query, queryRecord
- [#3762](https://github.com/emberjs/data/pull/3762) [BUGFIX release] Improve links vs. local data for relationships
- [#3701](https://github.com/emberjs/data/pull/3701) [BUGFIX release] fix regression where dynamically set id is not serialized in a create…
- [#3714](https://github.com/emberjs/data/pull/3714) Update the location of the custom store in the API doc example
- [#3717](https://github.com/emberjs/data/pull/3717) Remove Fixture Adapter
- [#3722](https://github.com/emberjs/data/pull/3722) Shape and cleanup
- [#3732](https://github.com/emberjs/data/pull/3732) follow up fixes for #3701
- [#3641](https://github.com/emberjs/data/pull/3641) Improve InternalModel (2x - 3x faster)
- [#3649](https://github.com/emberjs/data/pull/3649) Empty object
- [#3647](https://github.com/emberjs/data/pull/3647) Adapter.query should be part of the public overrideable interface.

### Release 2.0.1 (September 17, 2015)

- [#3751](https://github.com/emberjs/data/pull/3751) Remove normalizePayload, associated docs, and mention of functionality.
- [#3762](https://github.com/emberjs/data/pull/3762) [BUGFIX release] Improve links vs. local data for relationships
- [#3767](https://github.com/emberjs/data/pull/3767) [BUGFIX release] Do not export jsdoc information for store helper fun…
- [#3771](https://github.com/emberjs/data/pull/3771) update coalesceFindRequests doc for JSONAPIAdapter
- [#3776](https://github.com/emberjs/data/pull/3776) [BUGFIX release] Remove deprecation for old InvalidErrors format
- [#3778](https://github.com/emberjs/data/pull/3778) [BUGFIX release] Remove deprecation on store.filter
- [#3779](https://github.com/emberjs/data/pull/3779) [BUGFIX release] Remove store method deprecations
- [#3782](https://github.com/emberjs/data/pull/3782) [DOC release] Remove private label for findAll, query, queryRecord

### Release 2.0.0 (August 20, 2015)

#### Breaking Changes

##### Unsaved deleted records are no longer removed from hasMany relationships and RecordArrays returned by the store

In Ember Data 1.13 once a record was marked as deleted it was removed from all of the RecordArrays and hasMany arrays it belongTo. This made it difficult to create UIs where a user could flag a record for deletion but still allow the user the ability to un-flag the record until the save request was made.

In Ember Data 2.0 a record will no longer be removed from hasMany relationships or RecordArrays until the delete has been acknowledged by the adapter. Although deleted records will be visible in hasMany relationships they will not be serialized when saving these relationships to the backend.

#### Changes

- [#3665](https://github.com/emberjs/data/pull/3665) [BUGFIX beta] Fix usage of registry for 2.1.0+.
- [#3577](https://github.com/emberjs/data/pull/3577) Use the correct modelClass and serializer to extract a polymorphic ty…
- [#3669](https://github.com/emberjs/data/pull/3669) [DOC beta] Changed references to App.Person & App.Post in RESTAdapter API docs
- [#3636](https://github.com/emberjs/data/pull/3636) Add ember-cli-dependency-checker.
- [#3670](https://github.com/emberjs/data/pull/3670) [DOC beta] Change to decorator-style CPs in RESTAdapter API doc samples
- [#3651](https://github.com/emberjs/data/pull/3651) [DOC release] Update changelog for 1.13.9
- [#3653](https://github.com/emberjs/data/pull/3653) [BUGFIX beta] Update the dependencies for Ember 2.0
- [#3654](https://github.com/emberjs/data/pull/3654) Revert the live filterBy changes in Ember Data beta.1
- [#3656](https://github.com/emberjs/data/pull/3656) Update the changelog for 2.0.0-beta.2
- [#3661](https://github.com/emberjs/data/pull/3661) [DOC beta] Changed @default adapter from RESTAdapter to JSONAPIAdapter
- [#3666](https://github.com/emberjs/data/pull/3666) [BUGFIX beta] Initializer/Instance Initializer Deprecations.
- [#3672](https://github.com/emberjs/data/pull/3672) [DOC beta] Changed remaining CPs to decorator-style in RESTAdapter apidocs sample
- [#3680](https://github.com/emberjs/data/pull/3680) [BUGFIX beta] Prefer the new injection methods.
- [#3681](https://github.com/emberjs/data/pull/3681) [BUGFIX beta] Update required methods for the Serializer class
- [#3651](https://github.com/emberjs/data/pull/3651) [DOC release] Update changelog for 1.13.9
- [#3653](https://github.com/emberjs/data/pull/3653) [BUGFIX beta] Update the dependencies for Ember 2.0
- [#3654](https://github.com/emberjs/data/pull/3654) Revert the live filterBy changes in Ember Data beta.1
- [#3375](https://github.com/emberjs/data/pull/3375) JSONAPISerializer only supports the new Serializer API
- [#3251](https://github.com/emberjs/data/pull/3251) Convert unload test to json api format for `store.push`.. #3223
- [#3345](https://github.com/emberjs/data/pull/3345) [CLEANUP] drop IE8 support
- [#3487](https://github.com/emberjs/data/pull/3487) Default to using the JSONAPIAdapter
- [#3389](https://github.com/emberjs/data/pull/3389) Re-enable beta and canary tests
- [#3383](https://github.com/emberjs/data/pull/3383) update ember-inflector to 1.6.2
- [#3384](https://github.com/emberjs/data/pull/3384) Assert if the RESTSerializers when using the new format calls another
- [#3379](https://github.com/emberjs/data/pull/3379) store.push should support arrays in the JSONAPI data property
- [#3388](https://github.com/emberjs/data/pull/3388) Have looked up ActiveModelSerializer opt into the new Serializer API
- [#3489](https://github.com/emberjs/data/pull/3489) Remove deprecated code from the Ember Data initializer
- [#3396](https://github.com/emberjs/data/pull/3396) make sure deprecate error doesnt get swallowed when using store.push(type, data)
- [#3392](https://github.com/emberjs/data/pull/3392) AMS modelNameFromPayloadKey and serializePolymorphicType cleanup
- [#3394](https://github.com/emberjs/data/pull/3394) [DOC] Deprecate store.pushMany in documentation
- [#3408](https://github.com/emberjs/data/pull/3408) Fix Typos in Documentation for DS.Adapter
- [#3433](https://github.com/emberjs/data/pull/3433) Fix deprecation warnings
- [#3430](https://github.com/emberjs/data/pull/3430) [CLEANUP beta] Remove old Serializer API
- [#3432](https://github.com/emberjs/data/pull/3432) [CLEANUP beta] Use Object.keys/Object.create instead of Ember.keys/Ember.create
- [#3420](https://github.com/emberjs/data/pull/3420) [CLEANUP] Remove ember-new-computed dependency
- [#3410](https://github.com/emberjs/data/pull/3410) Fix minor typo in deprecation warning
- [#3488](https://github.com/emberjs/data/pull/3488) Relationships are async by default in 2.0
- [#3462](https://github.com/emberjs/data/pull/3462) Fix documentation typos in Adapter
- [#3441](https://github.com/emberjs/data/pull/3441) [CLEANUP beta] Remove ManyArray deprecations
- [#3440](https://github.com/emberjs/data/pull/3440) [CLEANUP beta] Remove RESTSerializer deprecations
- [#3439](https://github.com/emberjs/data/pull/3439) [CLEANUP beta] Remove RESTAdapter deprecations
- [#3438](https://github.com/emberjs/data/pull/3438) [CLEANUP beta] Remove BuildURLMixin deprecations
- [#3442](https://github.com/emberjs/data/pull/3442) [CLEANUP beta] Remove Model deprecations
- [#3443](https://github.com/emberjs/data/pull/3443) [CLEANUP beta] Remove Snapshot deprecations
- [#3436](https://github.com/emberjs/data/pull/3436) Fix Ember Data build with fresh install
- [#3457](https://github.com/emberjs/data/pull/3457) [CLEANUP beta] Remove ActiveModelAdapter/Serializer
- [#3458](https://github.com/emberjs/data/pull/3458) [DOC] createRecord relationships close #3421
- [#3490](https://github.com/emberjs/data/pull/3490) Remove deprecated finder methods on the store.
- [#3469](https://github.com/emberjs/data/pull/3469) Update shouldReload\* flags for 2.0
- [#3470](https://github.com/emberjs/data/pull/3470) Fix broken link
- [#3473](https://github.com/emberjs/data/pull/3473) [DOC] Fill @property of DS.Model.modelName
- [#3481](https://github.com/emberjs/data/pull/3481) update errors.js docs to mirror new json api error specs
- [#3477](https://github.com/emberjs/data/pull/3477) Add modelClass argument to JSONSerializer.extractId
- [#3539](https://github.com/emberjs/data/pull/3539) Only remove deleted records form record arrays when saved
- [#3496](https://github.com/emberjs/data/pull/3496) Update README.md
- [#3497](https://github.com/emberjs/data/pull/3497) Use `detail` instead of `details` for JSON API error objects
- [#3532](https://github.com/emberjs/data/pull/3532) [CLEANUP beta] Remove Store deprecations
- [#3550](https://github.com/emberjs/data/pull/3550) Fix JSONSerializer to pass through `payload.included`
- [#3534](https://github.com/emberjs/data/pull/3534) Rename error attribute
- [#3544](https://github.com/emberjs/data/pull/3544) Add error message in \_pushInternalMessage when unknown type
- [#3531](https://github.com/emberjs/data/pull/3531) Adds some documentation for JSONApiSerializer
- [#3533](https://github.com/emberjs/data/pull/3533) [CLEANUP beta] Remove console.log() call
- [#3567](https://github.com/emberjs/data/pull/3567) Use Ember.\$ instead of jQuery for AJAX requests
- [#3570](https://github.com/emberjs/data/pull/3570) Update `Ember.deprecate` and `Ember.warn` calls to include required information

### Release 1.13.16 (February 9, 2016)

- [#4143](https://github.com/emberjs/data/pull/4143) Update Ember
  Inflector and correct Ember Data's usage of it so that users' default
  custom inflections work.

### Release 1.13.15 (November 9, 2015)

- [#3876](https://github.com/emberjs/data/pull/3876) [BACKPORT][bugfix beta] serialize type for embedded, polymorphic belongsTo
- [#3891](https://github.com/emberjs/data/pull/3891) Don't use Ember.create by default

### Release 1.13.14 (October 18, 2015)

- [#3665](https://github.com/emberjs/data/pull/3665) [BUGFIX beta] Fix usage of registry for 2.1.0+.
- [#3825](https://github.com/emberjs/data/pull/3825) [BUGFIX] Restore IE8 compatibility by using Ember.create
- [#3837](https://github.com/emberjs/data/pull/3837) [BUGFIX] Attribute/relationship named "type" of embedded record is considered before normalization
- [#3840](https://github.com/emberjs/data/pull/3840) Backport Fix usage of registry for 2.1.0+ from pr #3665
- [#3846](https://github.com/emberjs/data/pull/3846) [BUGFIX beta] Attribute/relationship named "type" of primary record i…
- [#3847](https://github.com/emberjs/data/pull/3847) [BUGFIX beta] JSONAPI serializer not respecting 'attrs' hash
- [#3857](https://github.com/emberjs/data/pull/3857) [BUGFIX beta] rollbackAttributes() works after multiple failed saves
- [#3859](https://github.com/emberjs/data/pull/3859) [BUGFIX beta] Correctly handle invalid errors without payload or pointer

### Release 1.13.13 (September 17, 2015)

- [#3762](https://github.com/emberjs/data/pull/3762) [BUGFIX release]
  Improve links vs. local data for relationships

### Release 1.13.12 (September 10, 2015)

- [#3689](https://github.com/emberjs/data/pull/3689) Backport
  empty-object performance improvements from 2.1.0-beta1
- [#3690](https://github.com/emberjs/data/pull/3690)
  [BUGFIX release-1-13] Ensure that `service:store` is cleared before
  regsitering.
- [#3725](https://github.com/emberjs/data/pull/3725)
  [BUGFIX release-1-13] Disable polymorphic deserialization when a
  mode…
- [#3753](https://github.com/emberjs/data/pull/3753) Bumped the
  ember-inflector version to 1.9.2.
- [#3754](https://github.com/emberjs/data/pull/3754) Do not run tests
  with Ember 2.0 in the Ember Data 1.13 appveyor builds

### Release 1.13.11 (August 21, 2015)

- [#3685](https://github.com/emberjs/data/pull/3685) Fixing typo that
  causes Ember-Data v1.13.10 to crash with Ember v2.0.
- [#3686](https://github.com/emberjs/data/pull/3686) Fix broken
  rest-serializer test.

### Release 1.13.10 (August 20, 2015)

- [#3577](https://github.com/emberjs/data/pull/3577) Use the correct
  modelClass and serializer to extract a polymorphic
- [#3667](https://github.com/emberjs/data/pull/3667) Don’t crash \w
  Ember 2.0

### Release 1.13.9 (August 13, 2015)

#### Breaking Changes

The live updating `filterBy` on RecordArrays and ManyArrays has been
reverted because it broke existing applications. See
[#3263](https://github.com/emberjs/data/pull/3263).

#### Changes

- [#3633](https://github.com/emberjs/data/pull/3633) Fixed typo.
- [#3639](https://github.com/emberjs/data/pull/3639) Remove todo in API doc
- [#3648](https://github.com/emberjs/data/pull/3648) Revert filter by
- [#3623](https://github.com/emberjs/data/pull/3623) [BUGFIX release] Update ember-inflector to 1.9.0 (This commit was included in 1.13.8 but 1.13.8 was built with an old ember-inflector dependency by mistake.)

### Release 1.13.8 (August 5, 2015)

- [#3608](https://github.com/emberjs/data/pull/3608) [BUGFIX release] Validate JSON API docs returned by normalizeResponse
- [#3591](https://github.com/emberjs/data/pull/3591) `DS.Store#findQuery` overrides `DS.Store#query` docs
- [#3263](https://github.com/emberjs/data/pull/3263) Add `RecordArray#filterBy` which contains a live, filtered subset
- [#3593](https://github.com/emberjs/data/pull/3593) Update bin/changelog with customizations for Ember Data
- [#3601](https://github.com/emberjs/data/pull/3601) [DOC release] Fix missing docs due to /\* instead of /\*\*
- [#3610](https://github.com/emberjs/data/pull/3610) [BUGFIX release] Add missing urlForFindQueryRecord to BuildUrlMixin
- [#3615](https://github.com/emberjs/data/pull/3615) [DOC release] Update misleading example for Adapter.queryRecord()
- [#3619](https://github.com/emberjs/data/pull/3619) [DOC release] fix urlForFindRecord documentation
- [#3622](https://github.com/emberjs/data/pull/3622) Fix failing tests from merging PR #3263
- [#3623](https://github.com/emberjs/data/pull/3623) [BUGFIX release] Update ember-inflector to 1.9.0
- [#3624](https://github.com/emberjs/data/pull/3624) Implement filterBy on DS.ManyArray

### Release 1.13.7 (July 27, 2015)

- [#3554](https://github.com/emberjs/data/pull/3554) Add queryRecord method to the RESTAdapter
- [#3553](https://github.com/emberjs/data/pull/3553) Reversed args in Ember.Observer
- [#3531](https://github.com/emberjs/data/pull/3531) Adds some documentation for JSONApiSerializer
- [#3555](https://github.com/emberjs/data/pull/3555) [BUGFIX release] Transition to loaded.saved state after rollback
- [#3558](https://github.com/emberjs/data/pull/3558) [BUGFIX release] Follow JSON-API error object spec
- [#3560](https://github.com/emberjs/data/pull/3560) Deprecate error property
- [#3562](https://github.com/emberjs/data/pull/3562) remove babel warnings around parameters
- [#3563](https://github.com/emberjs/data/pull/3563) [DOC release] Adding documentation for SnapshotRecordArray
- [#3571](https://github.com/emberjs/data/pull/3571) [DOC release] Update README examples
- [#3575](https://github.com/emberjs/data/pull/3575) [BUGFIX release] Update `Ember.deprecate` and `Ember.warn` calls to include required information
- [#3582](https://github.com/emberjs/data/pull/3582) [BUGFIX release] Fix unconsistent behavior in Model.changedAttributes
- [#3590](https://github.com/emberjs/data/pull/3590) Update bin/changelog to deal with cherry-picked commits

### Release 1.13.6 (July 21, 2015)

- [#3564](https://github.com/emberjs/data/pull/3564) [BUGFIX release] backport ActiveModelAdapter changes [@fivetanley](https://github.com/fivetanley)
- [#3569](https://github.com/emberjs/data/pull/3569) [BUGFIX release] squash normalizePayload deprecations [@fivetanley](https://github.com/fivetanley)
- [BUGFIX release] fix some code for IE8 compat in ActiveModelSerializer
- [#3544](https://github.com/emberjs/data/pull/3544)[BUGFIX release] Add error message in \_pushInternalMessage when unknown type [@serabe](https://github.com/Serabe)
- [#3550](https://github.com/emberjs/data/pull/3550)[BUGFIX release] JSONSerializer pass through `payload.included`[@tstirrat](https://github.com/tstirrat)
- [#3534](https://github.com/emberjs/data/pull/3534)[DOC release] Rename `error` to `adapterError` [@tchak](https://github.com/tchak)
- [#3550](https://github.com/emberjs/data/pull/3550)[BUGFIX release] JSONSerializer pass through `payload.included` [@tstirrat](https://github.com/tstirrat)

### Release 1.13.5 (July 8, 2015)

- [#3437](https://github.com/emberjs/data/pull/3437) Deprecate normalizePayload and normalizeHash [@wecc](https://github.com/wecc)
- [#3478](https://github.com/emberjs/data/pull/3478) Fix Ember Data build with fresh install [@sly7-7](https://github.com/sly7-7)
- [#3475](https://github.com/emberjs/data/pull/3475) [BUGFIX release] Remove deprecation warning for dev, keep IE 8 compat [@sly7-7](https://github.com/sly7-7)
- [#3452](https://github.com/emberjs/data/pull/3452) [BUGFIX release] handle case where linked relationship data is null [@pangratz](https://github.com/pangratz)
- [#3458](https://github.com/emberjs/data/pull/3458) [DOC] createRecord relationships close #3421 [@givanse](https://github.com/givanse)
- [#3460](https://github.com/emberjs/data/pull/3460) [BUGFIX release] Do not register the service store when it has already been registered [@loadimpact](https://github.com/loadimpact)
- [#3462](https://github.com/emberjs/data/pull/3462) Fix documentation typos in Adapter [@sutherland](https://github.com/sutherland)
- [#3473](https://github.com/emberjs/data/pull/3473) [DOC] Fill @property of DS.Model.modelName [@XrXr](https://github.com/XrXr)
- [#3479](https://github.com/emberjs/data/pull/3479) [DOC release] Fix typo in JSONSerializer.extractAttributes docs [@pdud](https://github.com/pdud)
- [#3482](https://github.com/emberjs/data/pull/3482) [BUGFIX release] Update the version of ember-new-computed to fix an E… [@bmac](https://github.com/bmac)
- [#3481](https://github.com/emberjs/data/pull/3481) update errors.js docs to mirror new json api error specs [@philipp-spiess](https://github.com/philipp-spiess)
- [#3497](https://github.com/emberjs/data/pull/3497) Use `detail` instead of `details` for JSON API error objects [@sebastianseilund](https://github.com/sebastianseilund)
- [#3503](https://github.com/emberjs/data/pull/3503) [DOC release] Fix documentation for DS.InternalModel#\_changedKeys() [@hibariya](https://github.com/hibariya)
- [#3505](https://github.com/emberjs/data/pull/3505) [BUGFIX release] Do not assume the serializer is an Ember object. [@bmac](https://github.com/bmac)
- [#3511](https://github.com/emberjs/data/pull/3511) Assert serializers are using the same API [@wecc](https://github.com/wecc)
- [#3468](https://github.com/emberjs/data/pull/3468) [BUGFIX release] shouldReloadRecord and shouldBackgroundReloadRecord … [@bmac](https://github.com/bmac)
- [#3513](https://github.com/emberjs/data/pull/3513) [BUGFIX release] Always look up the serializer using store.serializerFor [@bmac](https://github.com/bmac)
- [#3477](https://github.com/emberjs/data/pull/3477) Add modelClass argument to JSONSerializer.extractId [@pdud](https://github.com/pdud)

### Release 1.13.4 (June 22, 2015)

- [#3398](https://github.com/emberjs/data/pull/3398) [REGRESSION release] Make meta available with new Serializer API [@wecc](https://github.com/wecc)
- [#3400](https://github.com/emberjs/data/pull/3400) [BUGFIX release] Correctly serialize type for hasMany relationships [@wecc](https://github.com/wecc)
- [#3408](https://github.com/emberjs/data/pull/3408) Fix Typos in Documentation for DS.Adapter [@heathharrelson](https://github.com/heathharrelson)
- [#3409](https://github.com/emberjs/data/pull/3409) [BUGFIX release] JSONAPISerializer missing pushPayload [@wecc](https://github.com/wecc)
- [#3410](https://github.com/emberjs/data/pull/3410) Fix minor typo in deprecation warning [@Dhaulagiri](https://github.com/Dhaulagiri)
- [#3413](https://github.com/emberjs/data/pull/3413) [BUGFIX release] Sideloaded records are not pushed when saving [@wecc](https://github.com/wecc)
- [#3397](https://github.com/emberjs/data/pull/3397) [BUGFIX release] Use typeOf instead of isArray in `_normalizeSerializerPayload` [@wecc](https://github.com/wecc)
- [#3396](https://github.com/emberjs/data/pull/3396) make sure deprecate error doesnt get swallowed when using store.push(type, data) [@jcope2013](https://github.com/jcope2013)
- [#3411](https://github.com/emberjs/data/pull/3411) Remove some usages of enumerable utils that made it into the release branch [@bmac](https://github.com/bmac)

### Release 1.13.3 (June 19, 2015)

- [#3375](https://github.com/emberjs/data/pull/3375) JSONAPISerializer only supports the new Serializer API [@wecc](https://github.com/wecc)
- [#3379](https://github.com/emberjs/data/pull/3379) store.push should support arrays in the JSONAPI data property [@bmac](https://github.com/bmac)
- [#3384](https://github.com/emberjs/data/pull/3384) Assert if the RESTSerializers when using the new format calls another [@bmac](https://github.com/bmac)
- [#3388](https://github.com/emberjs/data/pull/3388) Have looked up ActiveModelSerializer opt into the new Serializer API [@wecc](https://github.com/wecc)

### Release 1.13.2 (June 18, 2015)

- [#3370](https://github.com/emberjs/data/pull/3370) Allow overwrite for deprecated adapters [@tricknotes](https://github.com/tricknotes)

### Release 1.13.1 (June 17, 2015)

- [#3369](https://github.com/emberjs/data/pull/3369) Fix deprecation message for store.shouldReloadAll [@pangratz](https://github.com/pangratz)
- [#3374](https://github.com/emberjs/data/pull/3374) fix jquery error handler [@tchak](https://github.com/tchak)

### Release 1.13 (June 16, 2015)

- [#3143](https://github.com/emberjs/data/pull/3143) Refactor the Serializer API [@emberjs](https://github.com/emberjs)
- [#2904](https://github.com/emberjs/data/pull/2904) Implement basic JSON-API adapter [@wecc](https://github.com/wecc)
- [#2584](https://github.com/emberjs/data/pull/2584) Add queryOne method [@thaume](https://github.com/thaume)
- [#3310](https://github.com/emberjs/data/pull/3310) Allow the store to pass adapter options to the adapter [@bmac](https://github.com/bmac)
- [#3194](https://github.com/emberjs/data/pull/3194) Json api errors [@tchak](https://github.com/tchak)
- [#3235](https://github.com/emberjs/data/pull/3235) rename store.findQuery to store.query [@csantero](https://github.com/csantero)
- [#3232](https://github.com/emberjs/data/pull/3232) Add findByRecord and deprecate findById [@HeroicEric](https://github.com/HeroicEric)
- [#3167](https://github.com/emberjs/data/pull/3167) store.all() is not treated as a filteredRecordArray anymore [@pangratz](https://github.com/pangratz)
- [#3218](https://github.com/emberjs/data/pull/3218) Implement extractMeta for new Serializer API [@wecc](https://github.com/wecc)
- [#3226](https://github.com/emberjs/data/pull/3226) Warnings for incorrect options in belongsTo, resolves #3187 [@zoeesilcock](https://github.com/zoeesilcock)
- [#3234](https://github.com/emberjs/data/pull/3234) Make store.findAll(type) public [@HeroicEric](https://github.com/HeroicEric)
- [#3214](https://github.com/emberjs/data/pull/3214) serialize:true takes priority over the OneToMany check for relationships [@sly7-7](https://github.com/sly7-7)
- [#3216](https://github.com/emberjs/data/pull/3216) Record property changes [@bmac](https://github.com/bmac)
- [#3209](https://github.com/emberjs/data/pull/3209) Rename and deprecate finders (store.all -> store.peekAll and store.getById -> store.peekRecord) [@HeroicEric](https://github.com/HeroicEric)
- [#3221](https://github.com/emberjs/data/pull/3221) Metadata for hasmany [@emberjs](https://github.com/emberjs)
- [#3268](https://github.com/emberjs/data/pull/3268) Fix for passing json api objects into push [@emberjs](https://github.com/emberjs)
- [#3241](https://github.com/emberjs/data/pull/3241) Rename store.findByRecord to store.findRecord [@HeroicEric](https://github.com/HeroicEric)
- [#3253](https://github.com/emberjs/data/pull/3253) Treat empty strings in ids the same as null or undefined [@pangratz](https://github.com/pangratz)
- [#3262](https://github.com/emberjs/data/pull/3262) Pass \_internalModel into a record when it is created [@bmac](https://github.com/bmac)
- [#3340](https://github.com/emberjs/data/pull/3340) Use 'findRecord' instead of 'find' in doc [@emberjs](https://github.com/emberjs)
- [#3289](https://github.com/emberjs/data/pull/3289) Fix deprecation warning in tests [@bmac](https://github.com/bmac)
- [#3270](https://github.com/emberjs/data/pull/3270) Pass store to inverseFor in removeEmbeddedForeignKey [@wecc](https://github.com/wecc)
- [#3279](https://github.com/emberjs/data/pull/3279) Deprecation if id is Model in deserializeRecordId [@joelalejandro](https://github.com/joelalejandro)
- [#3286](https://github.com/emberjs/data/pull/3286) Deprecate `store:application` and `store:main` in favor of `service:store` [@bmac](https://github.com/bmac)
- [#3311](https://github.com/emberjs/data/pull/3311) Set the currentState when a record is created, not only when the stat… [@bmac](https://github.com/bmac)
- [#3290](https://github.com/emberjs/data/pull/3290) Rename `all` to `peekAll` in a test to fix a deprecation warning. [@bmac](https://github.com/bmac)
- [#3306](https://github.com/emberjs/data/pull/3306) Rename adapter and serializer methods to match the new store methods [@bmac](https://github.com/bmac)
- [#3312](https://github.com/emberjs/data/pull/3312) Deprecate fetch and replace it with store.findRecord(type, id, { reload: true}) [@bmac](https://github.com/bmac)
- [#3292](https://github.com/emberjs/data/pull/3292) Allow for store.push(object) [@emberjs](https://github.com/emberjs)
- [#3305](https://github.com/emberjs/data/pull/3305) Rename Model.rollback() to model.rollbackAttributes() [@HeroicEric](https://github.com/HeroicEric)
- [#3316](https://github.com/emberjs/data/pull/3316) Support custom stores defined on the container as [@bmac](https://github.com/bmac)
- [#3351](https://github.com/emberjs/data/pull/3351) Deprecate isDirty in favor of Model#hasDirtyAttributes [@bmac](https://github.com/bmac)
- [#3329](https://github.com/emberjs/data/pull/3329) Refactor `Errors#errorsByAttributeName` to not use Ember.reduceComputed [@pangratz](https://github.com/pangratz)
- [#3323](https://github.com/emberjs/data/pull/3323) Allow ember-source 2.x [@tricknotes](https://github.com/tricknotes)
- [#3324](https://github.com/emberjs/data/pull/3324) Implement adapter reload hooks from RFC #61 [@bmac](https://github.com/bmac)
- [#3326](https://github.com/emberjs/data/pull/3326) Deprecate store.pushMany in favor of store.push [@mikehollis](https://github.com/mikehollis)
- [#3334](https://github.com/emberjs/data/pull/3334) deprecate ActiveModelAdapter being bundled with core [@emberjs](https://github.com/emberjs)
- [#3362](https://github.com/emberjs/data/pull/3362) Improve deprecation for not using the new Serializer API [@wecc](https://github.com/wecc)
- [#3350](https://github.com/emberjs/data/pull/3350) Deprecate store.push(type, data) [@bmac](https://github.com/bmac)
- [#3344](https://github.com/emberjs/data/pull/3344) Disable beta and canary tests so we can ship Ember Data 1.13 that sti… [@bmac](https://github.com/bmac)
- [#3349](https://github.com/emberjs/data/pull/3349) Register service:store in an initializer instead of an instanceInitia… [@bmac](https://github.com/bmac)
- [#3346](https://github.com/emberjs/data/pull/3346) Remove the JSONAPI serializer refactor feature flag [@bmac](https://github.com/bmac)
- [#3347](https://github.com/emberjs/data/pull/3347) Implement modelNameFromPayloadKey in JSONSerializer [@wecc](https://github.com/wecc)
- [#3361](https://github.com/emberjs/data/pull/3361) Use MapWithDefault forEach instead of Array#forEach [@bmac](https://github.com/bmac)
- [#3364](https://github.com/emberjs/data/pull/3364) deprecate store.filter [@emberjs](https://github.com/emberjs)
- [#3365](https://github.com/emberjs/data/pull/3365) Convert internal representation to JSONApi [@bmac](https://github.com/bmac)
- [#3366](https://github.com/emberjs/data/pull/3366) Log a deprecation warning if users do not specify `async` on a relationship [@bmac](https://github.com/bmac)

### Release 1.0.0-beta.19.2 (June 12, 2015)

- Fix a regression with Ember CLI users who have defined a custom
  store in `app/store.js` - https://github.com/emberjs/data/pull/3316
- Fix a regression where `currentState` was not defined on a record
  until the record a state change occured. https://github.com/emberjs/data/pull/3311

### Release 1.0.0-beta.19.1 (June 9, 2015)

- Fix a regression where a `DS.Model`'s `InternalModel` would not be set
  on init - @bmac https://github.com/emberjs/data/pull/3262
- Pass store to inverseFor in removeEmbeddedForeignKey #3270 - @wecc
  https://github.com/emberjs/data/pull/3270

### Release 1.0.0-beta.19 (June 5, 2015)

#### Breaking Changes

##### Store Service moved to an Instance Initializer

In order to fix deprecations warning induced by Ember 1.12, the store service
is now injected as an instanceInitializer. As a consequence, if you had initializers
depending on the store, you should move them to an instance initializer as well,
and mark it as after: 'ember-data'.

- Removed support for DS.FixtureAdapter. You can use it as an addon, or
  build it using [Ember Giftwrap](https://github.com/ef4/ember-giftwrap).
  https://github.com/emberjs/ember-data-fixture-adapter/tree/master
- Removed support for passing factories to store methods. An example
  would be `store.find(App.Post, '1')`. Use the string form instead:
  `post` instead of `App.Post`. You can also use this [Ember Watson
  command](https://github.com/abuiles/ember-watson#ember-watsonconvert-ember-data-model-lookups)
- [#3074](https://github.com/emberjs/data/pull/3074) remove passing factories to store methods [@fivetanley](https://github.com/fivetanley)
- [#3083](https://github.com/emberjs/data/pull/3083) A new record which is marked as invalid can be rollbacked [@pangratz](https://github.com/pangratz)
- [#3102](https://github.com/emberjs/data/pull/3102) Updated copyright year [@perlun](https://github.com/perlun)
- [#3091](https://github.com/emberjs/data/pull/3091) deprecate support for DS.FixtureAdapter [@emberjs](https://github.com/emberjs)
- [#3097](https://github.com/emberjs/data/pull/3097) fix bower publishing [@emberjs](https://github.com/emberjs)
- [#3094](https://github.com/emberjs/data/pull/3094) Lazily materialize DS.Models for app code, use InternalModel inside ED otherwise [@emberjs](https://github.com/emberjs)
- [#3119](https://github.com/emberjs/data/pull/3119) maxUrlLength -> maxURLLength [@sly7-7](https://github.com/sly7-7)
- [#3110](https://github.com/emberjs/data/pull/3110) Cleanup unused 'materialize' records in model [@tonywok](https://github.com/tonywok)
- [#3182](https://github.com/emberjs/data/pull/3182) initialize lives on the application instance not the Ember namespace [@bmac](https://github.com/bmac)
- [#3126](https://github.com/emberjs/data/pull/3126) Guard for embedded unknown hasMany relationship [@wecc](https://github.com/wecc)
- [#3133](https://github.com/emberjs/data/pull/3133) Create snapshots on save not on flush [@tchak](https://github.com/tchak)
- [#3136](https://github.com/emberjs/data/pull/3136) Lookup the store using store:application instead of store:main [@bmac](https://github.com/bmac)
- [#3139](https://github.com/emberjs/data/pull/3139) Extend adapter instead of reopening it [@BookingSync](https://github.com/BookingSync)
- [#3138](https://github.com/emberjs/data/pull/3138) Custom primaryKey for embedded polymorphic relations work [@pangratz](https://github.com/pangratz)
- [#3174](https://github.com/emberjs/data/pull/3174) Adjust code samples to ember-cli [@Turbo87](https://github.com/Turbo87)
- [#3148](https://github.com/emberjs/data/pull/3148) add Snapshot#serialize method [@yratanov/feature](https://github.com/yratanov/feature)
- [#3170](https://github.com/emberjs/data/pull/3170) Ensure snapshot.belongsTo() and hasMany() do not return deleted records [@ianstarz](https://github.com/ianstarz)
- [#3156](https://github.com/emberjs/data/pull/3156) Remove deprecated push record [@sly7-7](https://github.com/sly7-7)
- [#3169](https://github.com/emberjs/data/pull/3169) rename add/removeRecord to add/removeInternalModel in record array [@sly7-7](https://github.com/sly7-7)
- [#3183](https://github.com/emberjs/data/pull/3183) fix belongs-to when set with a resolved promise [@sly7-7](https://github.com/sly7-7)
- [#3195](https://github.com/emberjs/data/pull/3195) Update comment to make its intention clearer [@bmac](https://github.com/bmac)
- [#3191](https://github.com/emberjs/data/pull/3191) refactor store managed instances [@fivetanley](https://github.com/fivetanley)
- [#3203](https://github.com/emberjs/data/pull/3203) Use string model names in debug adapter [@teddyzeenny](https://github.com/teddyzeenny)
- [#3208](https://github.com/emberjs/data/pull/3208) DirtyState.invalid handle pushedData event [@bmac](https://github.com/bmac)
- [#3211](https://github.com/emberjs/data/pull/3211) lookup JSONSerializer instance through store instead of manual instan… [@emberjs](https://github.com/emberjs)

### Release 1.0.0-beta.18 (May 18, 2015)

- [#3066](https://github.com/emberjs/data/pull/3066) Doc typo: primaryTypeClasss -> primaryTypeClass [@lolmaus](https://github.com/lolmaus)
- [#3058](https://github.com/emberjs/data/pull/3058) Fix changelog script to point to emberjs/data [@tonywok](https://github.com/tonywok)
- [#3034](https://github.com/emberjs/data/pull/3034) **POTENTIALLY BREAKING CHANGE if you override typeForRoot currently** introduce modelNameFromPayloadKey and deprecate typeForRoot [@fivetanley](https://github.com/emberjs)
  - `RESTSerializer#typeForRoot` has been deprecated. You can use
    `RESTSerializeer#modelNameFromPayloadKey` instead.
  - Added `RESTSerializer#payloadKeyFromModelName`. This allows you to
  - `typeKey` on Snapshots and Model classes has been deprecated. Use
    `modelName` instead.
    specify the outgoing root key for a JSON payload.
- [#3031](https://github.com/emberjs/data/pull/3031) Added pushedData hook to root.deleted.uncommitted state. [@aexmachina](https://github.com/aexmachina)
- [#3033](https://github.com/emberjs/data/pull/3033) dasherize ALL the things: use dasherized model names everywhere [@fivetanley](https://github.com/emberjs)
- [#3060](https://github.com/emberjs/data/pull/3060) Update changelog with correct-er links [@tonywok](https://github.com/tonywok)
- [#3065](https://github.com/emberjs/data/pull/3065) [DOC] update typo on #changedAttributes [@mateuspv](https://github.com/mateuspv)
- [#3068](https://github.com/emberjs/data/pull/3068) Fix incorrect documentation for RecordArray [@sberan](https://github.com/sberan)
- [#3073](https://github.com/emberjs/data/pull/3073) [DOCS] Added missing param to docs for generateIdForRecord [@joostdevries](https://github.com/joostdevries)
- [#3076](https://github.com/emberjs/data/pull/3076) Rely on active model serializer to handle error logic [@bdvholmes/bug](https://github.com/bdvholmes/bug)

### Release 1.0.0-beta.17 (May 10, 2015)

- [#2898](https://github.com/emberjs/data/pull/2898) Pass requestType to buildURL [@amiel](https://github.com/amiel)
- [#2790](https://github.com/emberjs/data/pull/2790) Embedded records mixin should use the correct serialization key when deserialize configuration is set, Fixes #2556 [@agrobbin](https://github.com/agrobbin)
- [#2933](https://github.com/emberjs/data/pull/2933) Extracts InvalidError into a separate file and makes it a subclass of Ember.Error [@twokul](https://github.com/twokul)
- [#2936](https://github.com/emberjs/data/pull/2936) Introduce relationship.hasData [@wecc](https://github.com/wecc)
- [#2940](https://github.com/emberjs/data/pull/2940) [DOC] Fix for DS.Store#findMany [@hibariya](https://github.com/hibariya)
- [#2939](https://github.com/emberjs/data/pull/2939) Snapshots unknown relationships [@wecc](https://github.com/wecc)
- [#2958](https://github.com/emberjs/data/pull/2958) adapter.serialize receives a snapshot [@rague](https://github.com/rague)
- [#2946](https://github.com/emberjs/data/pull/2946) Handle null/empty type paths in build url mixin [@vinilios](https://github.com/vinilios)
- [#2961](https://github.com/emberjs/data/pull/2961) Use new getter/setter for computed if available [@wecc](https://github.com/wecc)
- [#2956](https://github.com/emberjs/data/pull/2956) Clear meta data when unloading all records for a type. Fixes #2772 [@runspired](https://github.com/runspired)
- [#2953](https://github.com/emberjs/data/pull/2953) Do not assert reserved properties for static properties. [@bmac](https://github.com/bmac)
- [#2959](https://github.com/emberjs/data/pull/2959) Remove value from retrieveFromCurrentState CP [@wecc](https://github.com/wecc)
- [#2999](https://github.com/emberjs/data/pull/2999) Make unloadAll() unload all records, deprecate unloadAll(type) in favor ... [@svox1](https://github.com/svox1)
- [#2992](https://github.com/emberjs/data/pull/2992) Feature detect Ember.Registry rather than relying on version numbers [@emberjs](https://github.com/emberjs)
- [#2983](https://github.com/emberjs/data/pull/2983) Do not prepend a `/` if namespace is absolute. [@rwjblue](https://github.com/rwjblue)
- [#2966](https://github.com/emberjs/data/pull/2966) Break buildURL into multiple requestType methods [@thejameskyle](https://github.com/thejameskyle)
- [#2980](https://github.com/emberjs/data/pull/2980) [DOC] Use block params style {{#each}} [@HeroicEric](https://github.com/HeroicEric)
- [#2965](https://github.com/emberjs/data/pull/2965) Make version check for ember-data strict [@tricknotes](https://github.com/tricknotes)
- [#3035](https://github.com/emberjs/data/pull/3035) Add method argument to key serialization docs [@Dremora](https://github.com/Dremora)
- [#3004](https://github.com/emberjs/data/pull/3004) Fix serialization results in the documentation. [@nathanhammond](https://github.com/nathanhammond)
- [#3037](https://github.com/emberjs/data/pull/3037) Reset Model#isReloading to false when request fails [@pangratz](https://github.com/pangratz)
- [#3022](https://github.com/emberjs/data/pull/3022) Add missing urlForUpdateRecord to BuildURLMixin [@wecc](https://github.com/wecc)
- [#3021](https://github.com/emberjs/data/pull/3021) Remove unnecessary URL check in findHasMany [@wecc](https://github.com/wecc)
- [#3036](https://github.com/emberjs/data/pull/3036) Remove logic for camelCase-ing error keys in ActiveModelAdapter [@pangratz](https://github.com/pangratz)
- [#3030](https://github.com/emberjs/data/pull/3030) ActiveModelAdapter camelizes keys for errors on 422 [@bdvholmes](https://github.com/bdvholmes)
- [#3026](https://github.com/emberjs/data/pull/3026) [BUGFIX] AMS polymorphic type for namespaced models [@artych](https://github.com/artych)
- [#3032](https://github.com/emberjs/data/pull/3032) use typeKey and typeClass instead of using `type` inconsistently [@emberjs](https://github.com/emberjs)
- [#3040](https://github.com/emberjs/data/pull/3040) JSONSerializer#extractErrors respects custom key mappings [@pangratz](https://github.com/pangratz)
- [#3043](https://github.com/emberjs/data/pull/3043) Fix bug where record rejected via `find` stayed in loading state [@pangratz](https://github.com/pangratz)
- [#3046](https://github.com/emberjs/data/pull/3046) Documented the Model's `rolledBack` event [@lolmaus](https://github.com/lolmaus)
- [#3054](https://github.com/emberjs/data/pull/3054) Fix for deleting from ManyArray [@wagenet](https://github.com/wagenet)
- [#3055](https://github.com/emberjs/data/pull/3055) Merge `attrs` from superclasses into their subclasses. [@omghax](https://github.com/omghax)
- [#3056](https://github.com/emberjs/data/pull/3056) Add more assertions for merged attributes from superclass [@pangratz](https://github.com/pangratz)

### Release 1.0.0-beta.16.1 (March 24, 2015)

- Use ember-inflector 1.5
- Fix doc for Snapshot.attributes()
- Special case "application" in the store.serializerFor method
- Allow the store to lookup the applicationAdapter using adapterFor

### Release 1.0.0-beta.16 (March 23, 2015)

#### Breaking Changes

##### The store now passes snapshots instead of records to adapter methods

In 1.0.0-beta.15 serializers were updated to be passed snapshots instead of
records to prevent side-effects like fetching data when inspecting
relationships. This has now been extended to also include adapters methods.

The following adapter methods are now passed snapshots instead of records:

- `find(store, type, id, snapshot)`
- `findMany(store, type, ids, snapshots)`
- `findHasMany(store, snapshot, url, relationship)`
- `findBelongsTo(store, snapshot, url, relationship)`
- `createRecord(store, type, snapshot)`
- `updateRecord(store, type, snapshot)`
- `deleteRecord(store, type, snapshot)`

The signature of `buildURL(type, id, snapshot)` has also been updated to receive
snapshots instead of records.

This change removes the need for adapters to create snapshots manually using the
private API `record._createSnapshot()` to be able to pass snapshots to
serializers.

Snapshots are backwards-compatible with records (with deprecation warnings) and
it should be pretty straight forward to update current code to the public
Snapshot API:

```js
post.id           => postSnapshot.id
post.title        => postSnapshot.attr('title')
post.author       => postSnapshot.belongsTo('author')
post.comments     => postSnapshot.hasMany('comments')
post.constructor         => postSnapshot.type;
post.constructor.typeKey => postSnapshot.typeKey
```

If you need to access the underlying record of a snapshot you can do so by
accessing `snapshot.record`.

The full API reference of `DS.Snapshot` can be found [here](https://api.emberjs.com/ember-data/release/classes/Snapshot).

#### Changes

- Do not re-add deleted records to a hasMany relationship
- Shorten the list of reserved attributes on the model
- Remove \_createSnapshot() from DS.Snapshot documentation examples
- Pass snapshots to adapters instead of records
- Refactor the model assert so it will be correctly removed from the prod build.
- Adapters and Serializers are Store Managed
- Delete `Ember.required` (it is deprecated).
- Adding clearer wording for calling super form extract messages
- Missing parameter for JSDoc
- Add examples of how to use model.errors in a template
- Add doc example for defaultValue as a function on DS.attr
- Update the InvalidError docs to make it more clear about where the server payload gets normalized.
- Assert if the user tries to redefine a reserved property name.
- Remove container deprecation warnings in Ember Data tests
- hasRecordForId should return false if the record is not loaded
- [BUGFIX] fetching an empty record runs find
- bump ember-cli to 2.0 & remove sourcemapping comments in production
- commit record-arrays.js separately so it doesn't clobber the rename
- Rename local files to use dashes instead of underscores
- Have snapshots respect the order of items in hasMany relationships
- remove ManyArray from record_arrays
- update docs about `store` in serializer
- fetch() -> fetchById() in docs
- Run findHasMany inside an ED runloop
- Cleanup debug adapter test: Watching Records
- Fixed didDelete event/callback not fired in uncommited state
- Add main entry point for package.json.
- register the store as a service
- Warn when expected coalesced records are not found in the response
- Warn if calling attr, belongsTo or hasMany on model
- move Model to use default export instead of named export
- Move buildURL and related methods to a mixin
- Correct modelFor model not found errors
- Declare `store` property on DS.Model
- improve error message for belongsTo
- Move \_adapterRun onto the DS.Store object
- Move utility functions out of DS.Store, and into their own modules for reuse across ember-data
- CLean up implicit relationships on record unload
- Add assertion for `store` property on DS.Model subclasses
- Adds support for using mixins in polymorphic relationships
- [DOC]: Clarify when didCreate is fired
- (Docs) ManyArray is no longer a RecordArray
- Fix: root.deleted.invalid state

### Release 1.0.0-beta.15 (February 14, 2015)

#### Breaking Changes

##### serializer.serialize() now receives a Snapshot instead of a record instance

A snapshot represents the frozen state of a record at a particular
moment in time. Its initial purpose is to be passed to serializers
instead of the real record. This allows the serializer to examine the
current state of that record in the moment without triggering
side-effects, like loading relationships.

The serializer has a different API from a record for accessing
properties so you will know you are working with a snapshot. Using
`snapshot.get` is still supported for compatibility however it will
log a deprecated warning to encourage you to use the new apis.

To access attributes you should now use the `attr` function.

```js
// Ember Data 1.0.0-beta.14.1
post.title;
// Ember Data 1.0.0-beta.15
postSnapshot.attr('title');
```

To access a belongsTo relationship you should use `.belongsTo()` method.

```js
// Ember Data 1.0.0-beta.14.1
post.author;
// Ember Data 1.0.0-beta.15
postSnapshot.belongsTo('author');
```

To access a hasMany relationship you should use `.hasMany()` method.

```js
// Ember Data 1.0.0-beta.14.1
post.comments;
// Ember Data 1.0.0-beta.15
postSnapshot.hasMany('comments');
```

##### RecordArray.pushRecord and ManyArray.addRecord/removeRecord are deprecated

If you would like to add a new record to a `RecordArray` or a
`ManyArray` you should now use the `addObject` and `removeObject`
methods.

#### Changes

- use package.json for ember addon
- Initial implementation of the Snapshot API
- Allow errors on arbitrary properties, not just defined attributes or relationships
- Fix bug preventing hasMany relationships from correctly tracking simultaneous adds and removes.
- remove unused code.
- Deprecate store.dematerializeRecord()
- Use store.unloadRecord() in favor of store.dematerializeRecord()
- Correctly trigger arrayContentDidChange when updating hasMany relationships
- Warn if the user specifies a reflexive relationship without explicitly defining the inverse
- bump ember-inflector dependency for HTMLBars compat
- Add adapter.hasMany unique IDs test
- Replace calls to `container` with `registry`
- Dematerialize rejected \_find() if record isEmpty
- Add a Serializer base class
- Make ManyArray.save() and RecordArray.save() return themselves
- Added save() to ManyArray
- idiomatic super usage.
- Created `store.fetchById` and `store.fetchAll`.
- Update the generateIdForRecord docs to show it gets passed an Object not a record instance.
- Sort query params in ajax calls.
- Cleanup JSONSerializer#extract example
- Split Relationship Tests into Separate Files
- [DOCS]Update about defining application's store
- add documentation for the Store's find method
- Do not double include the host when it uses a protocol relative url.
- Deprecate RecordArray.pushRecord()
- Wrap the errorThrown in an Error object if it's a string.
- Use forEach instead of private api for accessing Map values
- Disable unknown keys warning by default
- remove type check for addCanonicalRecord in belongsto relationship
- Add support for embedded polymorphic belongsTo
- observers only fire for properties that changed
- Don't refilter .all() and .find() if only properties changed
- fixes to load beta 14/14.1 sourcemaps in ember-cli
- fix version for dropped <= Ember 1.7 support
- generateIdForRecord gets type & object properties passed to it
- Clarify store.find via findAll docs
- Deprecate addRecord/removeRecord for ManyArray

### Ember Data 1.0.0-beta.14.1 (December 31, 2014)

#### Changes

- Replace `<%= versionStamp %>` with actual version stamp. Thanks
  @tricknotes!
- Fix sourcemap loading in Ember CLI and Rails.

### Ember Data 1.0.0-beta.14 (December 25, 2014)

#### Breaking Changes

##### `store.update()` has been deprecated

Calling `store.update()` has been deprecated in favor of `store.push()` now
handling partial payloads:

```javascript
var post = store.push('post', {
  id: 1,
  title: 'Ember.js is fantastic',
  author: 'Tomster',
});

post.title; // => 'Ember.js is fantastic'
post.author; // => 'Tomster'

store.push('post', { id: 1, author: 'Tom Dale' });

post.title; // => 'Ember.js is fantastic'
post.author; // => 'Tom Dale'
```

This also mean that properties missing in the payload will no longer be reset,
but stay the same.

If you need to reset values to null, you should have your server explicitly
send back null values in the payload:

```javascript
{
  "person": {
    "firstName": null,
    "lastName": null
    "role": "Computer Science Pioneer"
  }
}
```

If you cannot change your API and you desire this behavior, you can create a
serializer and do the logic yourself:

```javascript
// app/serializers/person.js
// or App.PersonSerializer if you aren't using Ember CLI
export default DS.RESTSerializer.extend({
  normalize: function(type, hash, prop) {
    hash = this._super(type, hash, prop);
    if (!hash.hasOwnProperty('firstName')) {
      hash.firstName = null;
    }
    if (!hash.hasOwnProperty('lastName')) {
      hash.lastName = null;
    }
    return hash;
  },
});
```

Or if you want to restore the old behavior for all of your models:

```javascript
// app/serializers/application.js
// or App.ApplicationSerializer
export default DS.RESTSerializer.extend({
  normalize: function(type, hash, prop) {
    hash = this._super(type, hash, prop);
    type.eachAttribute(function(key) {
      if (!hash.hasOwnProperty(key)) {
        hash[key] = null;
      }
    }, this);
    return hash;
  },
});
```

##### `store.metaForType()` has been deprecated

`store.metaForType()` has been deprecated because of it's ambiguous naming.
Please use `store.metadataFor()` to get metadata and `store.setMetadataFor()`
to set metadata.

##### `ManyArray`s are no longer `RecordArray`s

[ManyArray](https://api.emberjs.com/ember-data/release/classes/ManyArray),
the object Ember Data uses to represent `DS.hasMany` relationships has
been changed so it no longer extends from `RecordArray`. This means if
you were relying on the RecordArray's `content` property to access the
underlying array you will now need to use the `.toArray()` method.

```javascript
// Ember Data 1.0.0-beta.12
record.myHasManyRelationship.content.map(...);

// Ember Data 1.0.0-beta.14
record.myHasManyRelationship.toArray().map(...);
```

Additionally if you were using the `RecordArray`'s `.addRecord()` and
`.removeRecord()` methods you will now need to use the `.addObject()`
/ `.removeObject()` array methods.

#### Changes

- Fix references to buildURL in documentation
- fix canary build for recent Ember.Container refactors
- [DOC] Stop using deprecated `each` helper syntax
- Work around type check issues with MODEL_FACTORY_INJECTIONS.
- [DOC] Add page for `DS.PromiseManyArray`
- [DOC] Fix markup for AcriveModelAdapter
- Add Ember.ENV.DS_NO_WARN_ON_UNUSED_KEYS option
- Fixed model rollback in the case where an attribute is not assigned so that it rolls back to unassigned instead of cached value. Added a supporting unit test.
- Fix array change notification in many arrays
- Use Ember.create and Ember.EnumerableUtils for relationships
- Backport pushing non async relationship as a link
- Backport relationship.proto.clear bugfix
- Schedule relationship normalization and split paths for canonical/client relationship updates
- fix DS.Errors#errorsFor documentation
- add test about model's attributes dirtiness
- Include build instructions in the readme
- Clarify that `store.fetch` documentation.
- Document and explicitely test specifying relationships type is optional
- Warn when pushing in a relationship as a link and its not an async relationship
- Removed unused notify on 'data' property
- fix Relationship.proto.clear bug
- Remove metaForType()/metadataFor() ambiguousness
- [Bugfix] promiseHasMany.reload() should return another promiseHasMany
- [Feature thrownError] tag errorThrown from jQuery onto the jqXHR like ic-ajax does.
- Cache relationships meta in production
- Deprecate store.update()
- hasMany relationships are no longer `RecordArray`, but `ManyArray`. To access the underlying array use `relationship.toArray()` instead of `relationship.content`.

### Ember Data 1.0.0-beta.12 (November 25, 2014)

##### Internet Explorer 8 Requires Ember 1.8

A bug in Ember 1.7's `Ember.create` method (which is a polyfill for
`Object.create`) combined with a bug in es5-shim's `Object.create` prevent us
from giving Ember Data users a good alternative to use. Internally, Ember Data
uses `Object.create` for efficient caches. Ember 1.8 ships a working
`Object.create` polyfill on `Ember.create` so if you are using Internet
Explorer 8 and Ember Data in production, you should upgrade to Ember 1.8 as
soon as you can.

If you are using browsers that provide `Object.create`, you do not need to do
any additional work here. This includes mobile browsers, evergreen browsers
(Chrome, Opera, Firefox), Safari, and IE9+.

##### Ember 1.7 Support Will Be Completely Dropped in Beta.13

Ember Data relies heavily on JavaScript language-level shims (such as the
`Object.create` issue mentioned above) and other useful internals that Ember
provides. Rather than creating our own detection algorithms and more polyfills
for broken code in Ember 1.7, we are deciding to drop 1.7 support in the next
release of Ember Data. We do so in order to not increase the final size of
Ember Data's build. You should upgrade to Ember 1.8 as soon as you can.

##### Observing `data` For Changes Has Been Removed

Although `model.data` has been private in Ember Data for a long time, we
have noticed users may subscribe to changes on `data` for any change to the
model's attributes. This means that the following code:

```javascript
var Post = DS.Model.extend({
  doSomethingWhenDataChanges: function() {
    // do the work
  }.property('data'),
});
```

**no longer works**. Instead, you should just watch each attribute like you
would with any `Ember.Object`:

```javascript
var Post = DS.Model.extend({
  name: DS.attr(),
  date: DS.attr(),
  doSomethingWhenDataChanges: function() {
    // do the work
  }.property('name', 'date'),
});
```

- Add Test Coverage for `ember-data/transforms`
- prefer Ember.create to Object.create
- Update the store.all docs to make it clearer that it only returns in-memory records.
- Allow async belongsTo to return null
- Add test for repeated failed model saves state
- Improve store.filter() docs
- Add more info about the store.fetch method
- Add tests for store#fetch
- Use store to call the find method
- Add fetch method to the store
- fix error propogating up through RSVP handler in tests
- update Ember.assert calls to check type
- Remove attr() data dependency
- Expand the package configuration filename glob declaration in `Brocfile.js` into the affected filenames, as the `broccoli-string-replace` plugin doesn't support globbing
- Clear inverseRecord for deleted belongsTo properly
- Warn when pushing unknown payload keys into the store
- RESTAdapter's buildURL from delete can ask for record's relations. closes #534
- Ensure production builds do not use require internally.
- [DOCS] InvalidError docs missing quote
- Use the model rollback and not state machine for created records rollback
- Relationship rollback from created state
- Don't allow empty strings as id in push/update
- Improve warns() test helper to better handle multiple calls
- `PromiseManyArray` proxies `Ember.Evented` methods to its `content`
- Extract function to proxy `PromiseManyArray`'s method to `content`
- createRecord on PromiseManyArray returns the new record instead of a Promise
- Add `createRecord` to PromiseArray so it proxies to ManyArray
- Nicer errors when pushing belongsTo/hasMany with invalid values
- Fixing an issue when grouping requests could result in URL longer than configured length.
- Refactored InvalidError handling into a serializer concern.
- [DOC] Fix usage of DS.Model.fields
- [DOC] Fix to apply js doc style to DS.ManyArray
- [DOC] Update usage of AMS
- [DOC] Fix typos in `ajaxSuccess`
- Added assertion for updateLink

### Ember Data 1.0.0-beta.11 _(October 13, 2014)_

- Rollback after delete record failure
- warn instead of throw when resolving keys to model
- added note about coalescing and custom URLs
- pass ids through encodeURIComponent when turning them into urls
- Always remove the inverse record (if exists) from a belongsTo relationship fixes #2331
- polyfill Ember.Map behavior
- use new Em.Map function signatures
- Refactor relationships with links
- Implemented rollbacking of implicit relationships
- Add support for rollback of relationships from deleted state
- Unwrap promises when setting a belongsTo
- Update tests on filters returning reloaded objects
- Update recordArrays when record has reloaded
- Refactor inverseFor cache
- Makes it possible to custom define inverses on only one side
- HasMany relationships now reload correctly
- Add a test for calling reload directly on the promiseProxy
- Add a test for reload on sync hasMany relationships
- Added a reload to the ManyArray
- [DOC fix] Remove misleading {inverse: null}
- Added implicit relationships
- Improve comments for the inverseFor method
- Serialize belongsTo where id===null as null
- [DOCS] Cleanup "USING EMBEDDED RECORDS" API readability
- preload the belongsTo to be available synchronously
- Add a test for an async belongsTo with buildURL
- removed private unused properties in ManyArray
- Small typo in #normalize documentation
- Do not clear own relationships when deleting records

### Ember Data 1.0.0-beta.10 _(September 9, 2014)_

**NOTE:** A bug was introduced in this version where the saving of a model with async hasMany property will send an empty list to the server in the payload, so is discouraged to use this version if you have such relationships on your application. For more details https://github.com/emberjs/data/issues/2339

- Bring back relationship parameter for findHasMany & findBelongsTo
- add es5-shim/sham requirement to README
- Add-on uses blueprint `addBowerPackageToProject()` hook to add ed as bower dep instead of including a pre-built version
- ember add-on vendor tree is relative to this file, so needs to go back a dir
- tests and typo fix for ajaxSuccess/ajaxError
- Add ajaxSuccess hook to the RESTAdapter
- Added ember-addon support via npm
- Update recordArrays whenever there are changes to relationships
- Refactor relationship handling code
- Add support for embedded polymorphic hasMany
- improve error message for push
- [BUGFIX] fixture adapter copies defined fixtures
- remove unused variables and enforce in jshint
- Updated docs to warn against use of async:true with EmbeddedRecodsMixin
- Removed a duplicate explanation of preload
- small perf, this map was unfortunately adding 5ms -> 8ms overhead for pushMany of N=1000. Removing it removed the overhead entirely.
- modelFor was used constantly, the extra normalization and string splitting was causing measurable slowdown.
- Don't use the DOM in the store tests
- Added an example of how to use the preload arg
- Added documentation for preload parameter
- [Documentation] typo in `find` documentation

### Ember Data 1.0.0-beta.9 _(August 18, 2014)_

**Important:** IE8 and other environments which don't support `Object.create`
correctly will need a shim for Object.create.

- bring in ember-inflector 1.1.0
- [DOCS] Add ids to RESTAdapter JSON payload examples
- [Doc] Fix typo, your, not you in DS.Store#update method comments
- [DOC] Add plural example for REST adapter.
- Substitute serialize:no to serialize:false in EmbeddedRecordsMixin
- Add support for JSONSerializer.attrs.key.serialize for `hasMany` and `belongsTo` relationships
- Refactor hasMany code for comments and clarity
- Batch hasMany requests with many id's to avoid max URL length issues
- Expose embedded options
- Changing an async belongsTo association does not load unfetched record.
- [Bugfix] relationship changes shouldn’t cause async fetches
- loosen constraint of adapter method return values
- Move EmbeddedRecordsMixin to core from activemodel
- Correct various yuidoc warnings to clean up some console noise when build the api docs
- factor out promise usage
- Do not serialize fixtures when deleting
- Refactor JSON serializer to use \_getMappedKey
- Don't normalize the key if not present in the hash
- Add serializeIntoHash to the JSON Serializer
- prefer new EmptyObject() for typeMap backing stores. Cache misses are faster, and won’t collide with prototype pollution
- since the recordArrayManager already maintains the uniq index, we can use that to simply push the record onto the record array without needing the safety of addRecords dupe guard. This prevents another O(n) operation
- the string splitting in transitionTo is wasteful and for large payloads can be surprisingly costly. As they never actually change, we should simply cache and forget about them.
- Coalesce find requests, add support for preloading data
- allow attributes to be excluded via the attrs hash
- DS.DateTransform now serializes to ISO8601 format by default. Adds millisecond precision to serializing dates
- Added id and requestType back to extract\* hooks
- Moved several normalize helper methods to the JSONSerializer - Move `normalizeAttributes` to the `JSONSerializer` (mirrors `serializeAttributes`) - Move `normalizeRelationships` to the `JSONSerializer` - Move `normalizePayload` to the `JSONSerializer`
- Throw an error if a user attempts to add a `data` property to a subclass of DS.Model
- Add a store.normalize() method to make it easy to normalize record data for store.push()
- Add a test for embedded belongsTo with a custom primaryKey
- Refactored EmbeddedRecordsMixin to push records instead of sideload
- PERF: O(n) -> O(1) record within recordArray check
- Add guard before deleting partial[attribute]
- Fixes embedded hasMany primary key lookup.
- Allow `attr` mapping in `belongsTo` & `hasMany` attributes;
- Favour declared mapping over keyForAttribute, if defined;
- improve debug ergonomics (as I debug)
- rest_adapter: Remove unused `set` definition
- Added documentation for ajaxError with DS.Errors.
- updated '\_links' to just 'links'
- Better error for missing inverse on hasMany/belongsTo
- adapt usage example for TemperatureTransform
- [Bugfix] Decouple DS.EmbeddedRecordsMixin from DS.ActiveModelSerializer

### Ember Data 1.0.0-beta.8 _(May 28, 2014)_

- Each RecordArray gets a copy of the models's metada object instead of sharing the same meta object. Enables several paginated arrays to coexist without clobbering each other
- Drop the `type` argument from `normalizePayload` calls. This argument was not consistently passed. Overridding the `extract` functions on the serializer is a suggested alternative if you require the model type.
- Introduce `DS._setupContainer()` for use in testing
- Deprecate the 5 Ember initializers, use just one named "ember-data"
- DS.EmbeddedRecordsMixin methods for serializing relationships call super if needed
- moved normalizeId to JSONSerializer
- JSONSerializer should use the attrs hash when extracting records Also breaks the \_super chain in normalize to preserve ordering in the RESTSerializer
- Remove unnessary loop in extracting single using DS.EmbeddedRecordsMixin
- Do not presume returned data arrays support .pushObjects
- [BUGFIX] store.fetchMany should always return a promise.
- Use keyForRelationship in JSONSerializer's serializeHasMany method
- Makes sure extractArray is normalizing each record in the array instead of trying to normalize the whole payload as an object.
- Do not cache model factories on meta, or on other model CPs
- Removed unused resolver from ManyArray.fetch
- normalizePayload only gets the payload
- [BUGFIX] Normalize typeKeys to always be camelCase
- Update the docs on pushPayload to clarify how model is used
- Put the initialization docs back with the initializers
- [DOC] Fix jsdoc for `Serializer#extractSingle`
- filteredRecordArray derived from filterFn + query, should retain its query (just as adapterPopulated does)
- Setting a filter function on a filteredRecordArray should only cause 1 re-filter per run-loop
- [Bugfix] when a record which exists in an adapterPopulatedRecordArray is destroyed, it is also now removed from the array
- [BUGFIX] Add missing support for belongsTo in DS.EmbeddedRecordsMixin
- Add support for serializing hasMany as ids
- incase jQuery.ajax returns a null or undefined jqXHR
- Fixes a typo in the documentation of the serializeAttribute method of json_serializer.js
- [DOC] `bower install` is part of `npm install`, removing it from README
- [DOC] Fix docs for method signature of extractSingle, extractArray
- Import InvalidError instead of looking at global DS
- allow saving records from invalid state
- [DOC beta] Clarify adapter settings with ActiveModel::Serializers
- Add examples to the DS.Errors api docs.
- Extend from Controller for ApplicationController.
- Update error messages from push and update
- Bring back deprecated initializers
- Refactor Ember initializer to use DS.\_setupContainer
- Fix incorrect documentation for isError.
- Explicitly define a bower install directory
- Import 'defaultRules', fixes missing Inflector.defaultRules
- Add an example of sending cookie information in the header and updated confusing reopen example.
- Expands isDeleted documentation
- Clarify adapter header documentation
- Documents invalid use of `attr` for attribute of `id`
- Store#pushPayload should use the type's serializer for normalizing
- Remove internal reliance on Ember.lookup.DS in favor of requireModule().
- Remove reliance on global DS
- Deprecate App.Store in favor of App.ApplicationStore.
- Remove `window` references in favor of `Ember.lookup`.
- Document the difference between Store push() vs. createRecord() ect.
- Document the store#update method.
- Make sure data adapter tests pass for Ember <= 1.4
- Update data adapter test with new Ember version
- change documentation from hash to payload
- Use the ApplicationAdapter property instead of creating a custom Store just to create a custom adapter.
- Use string model lookup instead of class lookup
- Improve store docs to use container lookup not concrete class
- Do not call adapter.deleteRecord for a record that is already saved and deleted
- Remove DS.AttributeChange
- Fix rollback on invalid record after set

### Ember Data 1.0.0-beta.7 _(February 19, 2014)_

- Release 1.0.0-beta.7
- Document required structure for DS.InvalidError
- Update ember version to 1.4.0
- lock server while compiling assets
- [DOC] Fix extractArray
- Don't pass the resolver where it's not needed
- force jshint on failure
- explicitly set a handlebars dependency to a version known to work.
- Remove Dead Code from RESTAdapter's Test
- Ensure the SHA is included in the VERSION.
- Destroying the store now:
- Revert "remove unneeded and misleading "async" test helpers"
- Break Down JSONSerializer#serializeBelongsTo Test
- remove unneeded and misleading "async" test helpers
- Wait on all the findMany promises to resolve before resolving the store#fetchMany promise.
- A records initial currentState can be on the prototype. Not need in doing the extra set on each init
- create promise labels outside of already visually complex code-paths
- reduce reusing argument variables, as it reduces clarity and makes debugging harder.
- hasMany relationship property are essentially readOnly, lets mark them as such.
- Improved assertion if an non-ember-data model has snuck in this far.
- Update instructions for running tests.
- Maintain consistency of internal changed attributes hash.
- Remove 0.13 era architecture file.
- Remove Ruby remnants.
- Add `grunt docs` task.
- Use local versions of grunt and bower for Travis.
- Do not generate a gzip report from uglify:dist.
- Add current revision back to build output.
- keep a local version of grunt-cli (dev only)
- Fix `grunt server` automated testing upon file change.
- Ensure builds are generated before publishing.
- Add build publishing to builds.emberjs.com.
- Fix the links to DS.Model and DS.Transform in the DS Namespace method docs
- Enable multi-channel testing.
- Allow testing against multiple versions of Ember & jQuery.
- Remove restriction for jQuery version in bower.json
- Object.create does not exist in old IE.
- Fix bug where an undefined id would trigger a `findAll`
- Avoid instance of aliasMethod due to problems with Chrome debugger
- Use latest stable Ember.js
- Cleanup. - Ember.computed takes the DK as a first argument, no need to all property on it again - misc formatting as I go.
- Upgrade QUnit to v1.13.0
- Use defeatureify to strip debug statements from output.
- Prefer Promise.cast over resolve.
- Use the new naming for active_model_adapter integration tests.
- Ensure that bower is installed.
- mark more model properties as readOnly
- allow connect port to be configurable
- misc cleanup
- once is already saved off at the top of the file
- add `grunt server`, and ensure the server(dev) version builds tests, so you can run tests
- postinstall bower install
- lazy create errors object on models
- Remove incorrect return documentation on store#pushPayload
- Pass arguments to `options.defaultValue` if a function.
- Revert "DateTransform serializes as a number instead of string. The deserializer was already considering this case. Adds millisecond precision to DateTransform"
- Should install grunt-cli globally.
- Now ember-data is built by `grunt buildPackages`
- Fix ember-data version
- Add missing task `grunt test`
- Export `Store` as default from ./system/store
- Use `expectDeprecation` helper in lookup tests
- Import `Store` instead of referencing it via `DS.Store`
- Register already imported transforms instead of `DS.XXX`
- Add `bower_components` to .gitignore
- Remove ruby-land tasks from Travis.
- Remove remnants of Ruby-land.
- Post release version bump.
- add grunt and bower install to .travis.yml
- update README with grunt workflow
- readd ContainerProxy to DS namespace
- fix build, import more test helper definitions from ember-dev
- fix banner generation a bit
- Do not trigger didSetProperty if value is unchanged.
- add watch option, fix some test oddities
- move some requires around
- move grunt tasks into folders
- ES6!

### Ember Data 1.0.0-beta.6 _(January 25, 2014)_

- DateTransform serializes as a number instead of string. The deserializer was already considering this case. Adds millisecond precision to DateTransform
- Remove unused helper.
- Updates DS.Model.rollback documentation
- Fix a typo in DS.filter doc
- Prefix built-in serializers and adapters with a dash.
- Spelling corrections in docs.
- Fix spelling in JSONSerializer class docs.
- Don't assume typeKey is always camelized.
- Deprecate former underscored names.
- Fix documentation for DS.Model.isNew
- [BUGFIX] Possible undefined errors in response via ActiveModelAdapter
- [BUGFIX] missing return statement in RecordArray#update
- Fixes a small typo in DS.Store deleteRecord docs
- Setting a property to undefined on a new record should not transition the record to root.deleted.saved
- Don't assume that factory.typeKey is always camelized.
- Normalize typeNames when comparing against typeKey.
- Force underscore after decamelizing typeKey.
- Set default Rakefile task to :test
- Remove underscores and rename
- The store's adapter property requires a string
- Rename dataAdapter to data-adapter
- Calls rake test[all] using bundle exec since CI was failing
- fixed behaviour of store.all() in combination with store.unloadAll() which caused elements to stay in the RecordArray, even if they should have been removed. ref #1611
- another quick fix, which should reduce run-loop pressure.
- Don't bother with Ember.run.once, as we can detect an impending flush by inspecting the size of the local queue of \_deferredTriggers

### Ember Data 1.0.0-beta.5 _(January 11, 2014)_

- Normalize key in modelFor when a factory is not given.
- `store.filter` should always return a FilteredRecordArray.
- attrs with options should allow for key option.
- Fix windows builds.
- Add DS.Errors object
- Handle case of single object pushPayload.
- Create RecordArrays from recordArrayManager.
- Documentation

### Ember Data 1.0.0-beta.4 _(December 19, 2013)_

- Use the adapter host for host-relative URLs in `findHasMany`.
- Fix `asyncBelongsTo` resolution.
- Add `destroyRecord` to delete and save a record at once.
- Make it easier to override just the Ajax options.
- Normalize hasMany polymorphic types for `DS.ActiveModelSerializer`.
- Add basic embedded record support to `DS.ActiveModelSerializer`.
- `DS.Store#modelFor` now assigns a store even when a factory supplied.
- Fixes adding unsaved records to hasMany relationships after they are normalized from saved payload.
- Correctly define window/global `DS` namespace in IE7/8.
- Test against all Ember channels.
- Allow `recordIsLoaded` to be called with a string for the type.
- Removing deleted records from RecordArrays is now async.
- Normalize `links` in `DS.RESTSerializer.normalize`.
- Label promises.
- Many documentation fixes.

### Ember Data 1.0.0-beta.3 _(September 28, 2013)_

- Add `normalizePayload` to `RESTAdapter` for payload normalization that is the same
  across all requests.
- Add `record.toJSON()`
- Normalize relationships on payloads returned from saves.
- Rename `rootForType` to `pathForType` in `RESTAdapter`
- Add `serializeIntoHash` in `RESTAdapter` to enable alternate root keys
- Print Ember Data version in the debug output when Ember boots
- Add `typeFromRoot`
- Allow retries of records that were not found
- Add `pushPayload` for pushing out of band records that still go through the
  appropriate normalization logic.
- Add an API for registering custom pluralization rules (see
  4df69d14ef2677977f520986070a2fdc45664008)
- Add `unloadAll` on store
- Infer the type of hasMany and belongsTo relationships by inflecting the key
- Polymorphic relationship improvements
- ActiveModel Adapter for working with Rails-like servers, not included by default
  in the Ember Data build but available separately.
- `store.metadataFor(type)` to get metadata provided by `findAll`.
- `RecordArray#save`
- `store.getById` returns null if a record isn't found
- Fix a number of rollback-related cases
- Fix async belongsTo
- A number of `links`-related fixes
- Ensure that `didLoad` fires when a record is created for the first time
- Support primary and sideloaded data of the same type to be returned from array
  lookups (via `posts` and `_posts`).
- IE8 fixes
- Add `record.changedAttributes()`
- Properly handle absolute and relative links in the `RESTAdapter`
- Records become clean again if their properties are set back to the original values

### Ember Data 1.0.0-beta.2 _(September 04, 2013)_

- Add support for `host` and `namespace` in the RESTAdapter
- Always use shorthand (`post`, not `App.Post`) in models
- Always use shorthand (`custom` not `App.CustomAdapter`) when looking up adapters
- Support `store.all('post')`
- Add back support for `record.rollback()`
- Transforms should be registered via `App.DateTransform` (for `date`)
- Add back support for `since` token for find all fetches
- Add `keyForAttribute` and `keyForRelationship` hooks in the serializer
- Support for serializing many-to-none and many-to-many relationships in RESTSerializer
- Several fixes for DS.hasMany async
- RESTAdapter `buildURL` takes a string, not type
- RESTAdapter now has `rootForType` to convert a type into the root
- `store.update` to update some, but not all attributes
- Thanks to Paul Chavard, Toran Billups, Bradley Priest, Kasper Tidemann, Yann Mainier,
  Dali Zheng, Jeremy Green, Robert Jackson, Joe Bartels, Alexandre de Oliveria,
  Floren Jaby, Gordon Hempton, Ivan Vanderbyl, Johannes Würbach, Márcio Júnior,
  Nick Ragaz, Ricardo Mendes, Ryunosuke SATO, Sylvain Mina, and ssured

### Ember Data 1.0.0-beta.1 _(September 01, 2013)_

- Added `DS.DebugAdapter` which extends `Ember.DataAdapter`
- Explain how to deal with embedded records
- Start on a transition guide
- Make willCommit while in flight a noop
- Update examples
- Move normalization and extraction to serializer
- `deleteRecord` when already deleted is a noop
- Explain "originally passed as an Array of IDs"
- Shortens unnecessary verbiage
- Add Promise Proxies
- Add back serializers
- More consistency for serializerFor
- Rename `NewJSONSerializer` to `JSONSerializer`
- Don't invalidate `data` if there's no new data
- Use the inflector instead of dumb pluralization
- `store.create({adapter:'name'})` uses the container
- Remove `resolveOn`
- Thread more promises through the adapter
- Fix invokeLifecycleCallbacks on still dirty record
- Initialize adapter in the store
- Support merging scenarios
- Start implementing merge semantics
- Remove references to references
- Remove unnecessary usage of references
- Remove leftover serializer code
- Add support for singular names in REST payloads
- Move extraction layers to adapter
- Added support for URL lookups
- Inject the default DS.Store if none is provided
- Add `findAll`, `findMany` and `findQuery` to RESTAdapter
- Add `findAll` plus request-type-specific extracts
- Make serializer respect primaryKey/attrs
- REST Adapter payload stuff
- Ember.Inflector: `Ember.String#pluralize` and `Ember.String#singularize`
- Remove `handlePromise` indirection.
- Queries are now using promises properly
- Share code between sync and async `hasMany`
- Unload test passing
- Adapter Interop test passing (plus findByIds)
- Get reloading passing
- Got record persistence test passing
- Records are no longer thenables
- Require application.Store to be defined - Fixes #1084
- Relationship changes operate on records
- Don't assign DS to window unless window exists - Fixes #681
- Client ID generation passing
- Eagerly generate the jQuery expando on window
- Allowing inverse relationships to be nullable.
- `fetchRecord` replaced `findById` here
- Eliminate lazy materialization from `belongsTo`
- Start consolidating API around records
- Make the data materialized again
- Add `debugInfo` to `DS.Model`
- Add `store.push` and `store.recordFor`
- Remove redundant `[]` from `Ember.A()` calls
- Bump ember-source
- Flatten model's `data` structure into single hash
- Fix deprecation warning
- Add serializerFor API to `DS.Store`
- Removed duplicate method declaration
- `save` method is not private
- Prevent resolution of jQuery's self fulfilling jqXHR thenable Since it resolves on another turn, it will cause needless and unwrappable auto-runs
- Rewrite the state machine to improve performance
- Add individual record to the buildURL signature.
- Update jQuery version for `rake test[all]`
- Remove unnecessary inspector for `object`
- Remove option to specify router
- Declared `ajaxHeaders`.
- Specify additional headers for RESTAdapter.
- Update supported ruby version
- Use `Ember.EnumerableUtils.map`
- Use `Ember.EnumerableUtils.indexOf`
- Use `Ember.EnumerableUtils.forEach`
- Modify code indent
- Bump ember-source to 1.0.0-rc.6
- Include the version number in the javascript.
- This expression makes my brain hurt, lets atleast expand this to two lines. (We need some sort of macro system to improve these assertions.
- Improve variable naming consistency
- Remove nested run loop.
- Allow metadata value to be zero
- Remove redundant serialized variable. :/
- Better serializeId implementation that takes empty strings into consideration and fixed a logic error in `isNaN(id)` check
- Id serialization correctly returns null for null or undefined id values rather than 0
- Remove bundled jQuery
- First pass at uncatchable assertions
- English, do you speak it?
- Remove unused variables
- Remove unused helper
- Remove unnecessary comment
- Remove unused tasks
- Support `Ember::Data::VERSION`
- Assert post is dirty
- Replace references to jQuery with Ember.$
- RESTAdapter: reject with xhr only
- Fix: record must be invalid on 422
- Add failing integration test to expose bug #1005
- Remove revision reference.
- Check against `null` and `undefined`

### Ember Data 0.13 _(May 28, 2013)_

- Initial Release
