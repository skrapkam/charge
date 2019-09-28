# Snapshot report for `test/build/jsx_test.js`

The actual snapshot is saved in `jsx_test.js.snap`.

Generated by [AVA](https://ava.li).

## loads data from data files and passes it to the JSX page

> Snapshot 1

    [
      'tmp/tests/target/index.html',
    ]

> Snapshot 2

    {
      'tmp/tests/target/index.html': `<!DOCTYPE html>␊
      ␊
      <p>bar</p>`,
    }

## renders a JSX page as HTML

> Snapshot 1

    [
      'tmp/tests/target/index.html',
    ]

> Snapshot 2

    {
      'tmp/tests/target/index.html': `<!DOCTYPE html>␊
      ␊
      <div></div>`,
    }

## renders a JSX page as HTML with a JSX component

> Snapshot 1

    [
      'tmp/tests/target/index.html',
    ]

> Snapshot 2

    {
      'tmp/tests/target/index.html': `<!DOCTYPE html>␊
      ␊
      <div><p>bar</p></div>`,
    }

## renders a JSX page as HTML with a JSX component as a layout

> Snapshot 1

    [
      'tmp/tests/target/index.html',
    ]

> Snapshot 2

    {
      'tmp/tests/target/index.html': `<!DOCTYPE html>␊
      ␊
      <div><p>foobar</p></div>`,
    }

## renders a JSX page as HTML with an MDX component

> Snapshot 1

    [
      'tmp/tests/target/index.html',
    ]

> Snapshot 2

    {
      'tmp/tests/target/index.html': `<!DOCTYPE html>␊
      ␊
      <div><h1>Heading</h1><h2>Subheading</h2></div>`,
    }