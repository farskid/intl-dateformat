# Snapshot report for `test/parseDate.ts`

The actual snapshot is saved in `parseDate.ts.snap`.

Generated by [AVA](https://ava.li).

## parse a date

> Snapshot 1

    {
      day: '17',
      dayPeriod: 'PM',
      dayperiod: 'PM',
      hour: '4',
      lhour: '16',
      lmonth: 'January',
      minute: '13',
      month: '01',
      second: '37',
      weekday: 'Tuesday',
      year: '1984',
    }

## parse a date with a custom locale

> Snapshot 1

    {
      day: '17',
      dayPeriod: undefined,
      hour: '16',
      lhour: '16',
      lmonth: 'janvier',
      minute: '13',
      month: '01',
      second: '37',
      weekday: 'mardi',
      year: '1984',
    }

## parse a date with a custom timezone

> Snapshot 1

    {
      day: '18',
      dayPeriod: 'AM',
      dayperiod: 'AM',
      hour: '12',
      lhour: '00',
      lmonth: 'January',
      minute: '13',
      month: '01',
      second: '37',
      weekday: 'Wednesday',
      year: '1984',
    }
