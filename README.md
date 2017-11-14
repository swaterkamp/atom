# atom
My Atom settings and features

Packages to install:

apm install language-babel
apm install linter-eslint

Add to init.coffee:
atom.context.add{
  'atom-workspace':[
      {label: 'Fixlint', command: linter_eslint:fix-file'}
  ]
}
