# Warn when there is a big PR
warn("Big PR") if git.lines_of_code > 500

# Look for prose issues
prose.lint_files

# Look for spelling issues
prose.ignored_words = %w(CocoaPods OSS NPM MVC JS JSX GraphQL Redux lockfile ESLint linter ES6 ES2016 ECMA SemVer Mutablilty destructuring typings v8 transpilation plugin plugins olde HTML5 CSS3 CSS HTML async vscode dangerfile UIView MVVM FRP TLDR: TLDR DangerJS)
prose.check_spellings

message("Test Message")

warn("You have not included a CHANGELOG entry.")

fail("Our linter has failed.")

markdown("## xxxxx")

warn("Please add your name", file: "CHANGELOG.md", line: 4)


simplecov.report('coverage/coverage.json')


todoist.warn_for_todos
todoist.print_todos_table

xcode_summary.ignored_files = '**/Pods/**'
xcode_summary.report 'xcodebuild.json'