##Réponse de ART

##Commande Utilisée
grep -r '"_from":' node_modules/**/package.json | cut -d ':' -f 3 | sed 's/"//g' | sort -d | uniq

##Résultat Obtenu
 acorn@6.0.4
 acorn-jsx@5.0.1
 ajv@6.6.2
 ansi-escapes@3.1.0
 ansi-regex@3.0.0
 ansi-styles@3.2.1
 argparse@1.0.9
 asn1@0.2.4
 assert-plus@1.0.0
 astral-regex@1.0.0
 asynckit@0.4.0
 aws-sign2@0.7.0
 balanced-match@1.0.0
 bcrypt-pbkdf@1.0.2
 bind-obj-methods@2.0.0
 bluebird@3.5.3
 brace-expansion@1.1.11
 browser-process-hrtime@1.0.0
 buffer-from@1.1.1
 caller-path@0.1.0
 callsites@0.2.0
 capture-stack-trace@1.0.1
 caseless@0.12.0
 chalk@2.3.0
 chardet@0.7.0
 circular-json@0.3.3
 clean-yaml-object@0.1.0
 cli-cursor@2.1.0
 cli-width@2.2.0
 color-convert@1.9.1
 color-name@1.1.3
 color-support@1.1.3
 commander@2.13.0
 concat-map@0.0.1
 core-util-is@1.0.2
 coveralls@3.0.0
 cross-spawn@6.0.5
 dashdash@1.14.1
 debug@4.1.1
 deep-is@0.1.3
 delayed-stream@1.0.0
 diff@1.4.0
 doctrine@2.1.0
 domain-browser@1.2.0
 ecc-jsbn@0.1.2
 escape-string-regexp@1.0.5
 eslint@5.11.0
 eslint-config-usecases@1.2.2
 eslint-scope@4.0.0
 eslint-utils@1.3.1
 eslint-visitor-keys@1.0.0
 espree@5.0.0
 esprima@4.0.1
 esquery@1.0.1
 esrecurse@4.2.1
 estraverse@4.2.0
 esutils@2.0.2
 events-to-array@1.1.2
 external-editor@3.0.3
 extsprintf@1.3.0
 fast-deep-equal@2.0.1
 fast-json-stable-stringify@2.0.0
 fast-levenshtein@2.0.6
 figures@2.0.0
 file-entry-cache@2.0.0
 flat-cache@1.3.4
 foreground-child@1.5.6
 forever-agent@0.6.1
 form-data@2.3.3
 fs-exists-cached@1.0.0
 fs.realpath@1.0.0
 functional-red-black-tree@1.0.1
 function-loop@1.0.1
 getpass@0.1.7
 glob@7.1.3
 globals@11.9.0
 graceful-fs@4.1.15
 growl@1.10.5
 har-schema@2.0.0
 har-validator@5.1.3
 has-flag@2.0.0
 hoek@6.1.2
 http-signature@1.2.0
 iconv-lite@0.4.24
 ignore@4.0.6
 imurmurhash@0.1.4
 inflight@1.0.6
 inherits@2.0.3
 inquirer@6.2.1
 isarray@1.0.0
 isemail@3.2.0
 isexe@2.0.0
 is-fullwidth-code-point@2.0.0
 is-promise@2.1.0
 isstream@0.1.2
 is-typedarray@1.0.0
 joi@14.3.0
 jsbn@0.1.1
 json-schema@0.2.3
 json-schema-traverse@0.4.1
 json-stable-stringify-without-jsonify@1.0.1
 json-stringify-safe@5.0.1
 jsprim@1.4.1
 js-tokens@4.0.0
 js-yaml@3.10.0
 lcov-parse@0.0.10
 levn@0.3.0
 lodash@4.17.11
 log-driver@1.2.5
 lru-cache@4.1.5
 mime-db@1.30.0
 mime-types@2.1.17
 mimic-fn@1.2.0
 minimatch@3.0.4
 minimist@0.0.8
 minipass@2.3.5
 mkdirp@0.5.1
 ms@2.1.1
 mute-stream@0.0.7
 natural-compare@1.4.0
 nice-try@1.0.5
 nyc@11.9.0
 object-assign@4.1.1
 once@1.4.0
 onetime@2.0.1
 opener@1.5.1
 optionator@0.8.2
 os-homedir@1.0.2
 os-tmpdir@1.0.2
 own-or@1.0.0
 own-or-env@1.0.1
 path-is-absolute@1.0.1
 path-is-inside@1.0.2
 path-key@2.0.1
 performance-now@2.1.0
 pluralize@7.0.0
 prelude-ls@1.1.2
 process-nextick-args@2.0.0
 progress@2.0.3
 pseudomap@1.0.2
 psl@1.1.31
 punycode@1.4.1
 qs@6.5.2
 readable-stream@2.3.6
 regexpp@2.0.1
 request@2.88.0
 require-uncached@1.0.3
 resolve-from@1.0.1
 restore-cursor@2.0.0
 rimraf@2.6.2
 run-async@2.3.0
 rxjs@6.3.3
 safe-buffer@5.1.1
 safer-buffer@2.1.2
 semver@5.6.0
 shebang-command@1.2.0
 shebang-regex@1.0.0
 signal-exit@3.0.2
 slice-ansi@2.0.0
 source-map@0.6.1
 source-map-support@0.5.9
 sprintf-js@1.0.3
 sshpk@1.16.0
 stack-utils@1.0.2
 string_decoder@1.1.1
 string-width@2.1.1
 strip-ansi@4.0.0
 strip-json-comments@2.0.1
 table@5.1.1
 tap@12.1.1
 tap-mocha-reporter@3.0.7
 tap-parser@7.0.0
 text-table@0.2.0
 through@2.3.8
 tmatch@4.0.0
 tmp@0.0.33
 topo@3.0.3
 trivial-deferred@1.0.1
 tsame@2.0.1
 tslib@1.9.3
 tunnel-agent@0.6.0
 tweetnacl@0.14.5
 type-check@0.3.2
 unicode-length@1.0.3
 uri-js@4.2.2
 util-deprecate@1.0.2
 verror@1.10.0
 which@1.3.1
 wordwrap@1.0.0
 wrappy@1.0.2
 write@0.2.1
 write-file-atomic@2.3.0
 yallist@2.1.2
 yapool@1.0.0

