## Travis Buddy
Hey **{{author}}**, 
We found no major flaw with your code. Still you might want to look at this logfile, as we usually suggest some optional improvements.

{{#jobs}}
### {{displayName}}
{{#scripts}}
<details>
  <summary>
    <strong>
     {{command}}
    </strong>
  </summary>

```
{{&contents}}
```
</details>
<br />
{{/scripts}}
{{/jobs}}
