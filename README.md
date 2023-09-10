# DatePicker-BenoitMouly REACT

This custom react datepicker could be useful for having a customizable datepicker, instead of having heavy libraries or traditionnal datepicker given by navigator.

## Available Scripts

In the project directory, you can run:

### `npm install datepicker-benoitmouly`

It installs needed depedencies

## Usage

```react
import DatePickerCustom from "datepicker-benoitmouly";

const [dateofbirth, setBirth] = useState("");

<DatePickerCustom label='Date de début de contrat' getDate={setBirth} className="startdate" />
```

- ' getDate ', function. It could be a validator or a useState. Required.
- ' label ', string. Optionnal.
- ' className', string. Optionnal.

## Stylizing

You can stylize it with their classes directly from the node modules. We prefered to give a basis of CSS to not interfer with your css rules.

## Depedencies

> dayjs,
> react

---------------
NPM version : 9.5.0

Latest test :

- dayjs 1.11.9
- react 18.2.0

[![forthebadge](https://forthebadge.com/images/badges/certified-elijah-wood.svg)](https://forthebadge.com) [![forthebadge](https://forthebadge.com/images/badges/made-with-javascript.svg)](https://forthebadge.com)
