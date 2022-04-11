# react-native-ammazza_live_tryon

Live try on module for ammazza clients

## Installation

```sh
npm install react-native-ammazza_live_tryon
```

## Usage

```js
import { LiveTryon } from "react-native-ammazza_live_tryon";

// ...

 <LiveTryon ref={instance => { this.state.child = instance; }}></LiveTryon>


  <Button
        title="Open tryon"
        onPress={() => this.state.child.openModelForproduct(ProductId, clientId)}
      />
```

## Contributing

See the [contributing guide](CONTRIBUTING.md) to learn how to contribute to the repository and the development workflow.

## License

Weboccult
