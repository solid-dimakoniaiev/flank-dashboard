# Metrics Web Application :tada: :c2heckdata-cat-cat-2-t:

The Flutter web application that displays project metrics on easy to navigate Dashboard.

## Getting Started :beginner:

This application is a part of Metrics project: make sure to get yourself familiar with the Metrics project documentation first. The web component documentation is located under the `docs` folder. 

Here is the easy to navigate list of these documents: 
1. [Metrics Web Application architecture :walking:](docs/01_metrics_web_application_architecture.md)
2. [Metrics Web presentation layer architecture :running:](docs/02_presentation_layer_architecture.md)
3. [Widget structure organization :bicyclist:](docs/03_widget_structure_organization.md)

## Setup :rocket:

Please use the [official documentation](https://flutter.dev/docs/get-started/install) to install & configure Flutter for web. Here are the relevant sections: 
1. System Requirements.
2. Get the Flutter SDK.
3. Run `flutter doctor`.
4. Update your `PATH`.

After the above steps are complete, use the following commands to ensure proper Flutter version installed and web is enabled:
```shell script
cd $(which flutter | xargs dirname) && git checkout 1.25.0-8.2.pre
flutter config --enable-web
```
_**Note:** The above commands works correctly on Unix based operating systems (verified: macOS and Ubuntu)! Before using, consider rewriting it according to your operating system._

That is, your machine is ready to run the Metrics Web Application! :champagne:

## Run :runner:

To run the Metrics Web Application, you can use your IDE runner with Chrome device selected. To run the application from command-line, use the following command:
```shell script
flutter run -d chrome
```
