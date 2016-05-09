Shameless clone of [angular-progress-arc](https://github.com/mathewbyrne/angular-progress-arc) rewritten to Angular 2.

### Example Usage

```
<progress-arc
  [progress]="myItem.downloadProgress()"
  [size]="30"
  [strokeColor]="'#00acee'"
  [backgroundColor]="'#f9fafb'">
 </progress-arc>
```

### Parameters

See [list of @Input params](https://github.com/petervojtek/angular2-progress-arc/blob/master/progress_arc.ts#L10) for default params you can override.

### Troubleshooting

* You app's `templateUrl` path may differ from the relative path in [source code](https://github.com/petervojtek/angular2-progress-arc/blob/master/progress_arc.ts#L6). E.g., in Ionic 2 you may need to rewrite it to `templateUrl: 'build/components/progress_arc/progress_arc.html'`
