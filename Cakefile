{ spawn } = require 'child_process'

task 'watch', 'watch jade, stylus and coffee', ->

  spawn 'jade', [
    '-o', 'htdocs'
    '-wP'
    'src'
  ],
    stdio: 'inherit'

  spawn 'stylus', [
    '-o', 'htdocs'
    '-w'
    'src'
  ],
    stdio: 'inherit'

  spawn 'coffee', [
    '-o', 'htdocs'
    '-wc'
    'src'
  ],
    stdio: 'inherit'
