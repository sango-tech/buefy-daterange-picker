# buefy-daterange-picker

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
