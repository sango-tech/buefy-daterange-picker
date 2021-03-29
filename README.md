# buefy-daterange-picker

![Screen Shot 0003-03-29 at 10 53 12](https://user-images.githubusercontent.com/9253378/112784944-0db1cd00-907d-11eb-9f26-4a976f021c38.png)


## Installation

``` bash
# install via npm
npm i buefy-daterange-picker --save
```

### Usage
```
import 'buefy-daterange-picker/dist/buefy-daterange-picker.css'
import DateRangePicker from 'buefy-daterange-picker'


<date-range-picker
    ref="picker"
    :opens="'left'"
    :locale-data="localeData"
    :singleDatePicker="false"
    :timePicker="true"
    :timePicker24Hour="true"
    :showWeekNumbers="true"
    :showDropdowns="true"
    :autoApply="false"
    v-model="dateRange"
    @update="handleSelectDateRange"
    :linkedCalendars="true"
    >
    <template v-slot:input="picker">
      <b-input :value="dateRangeFormated(picker)"></b-input>
    </template>
</date-range-picker>

</b-field>
```


### Run local demo
```
npm run docs:dev
```
