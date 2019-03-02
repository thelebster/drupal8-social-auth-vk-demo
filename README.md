# Drupal 8: Social Auth Vk Demo

Demo Drupal 8 installation to demonstrate the [Social Auth Vkontake module](https://www.drupal.org/project/social_auth_vk).

## Usage

Install the project:

```
composer install
```

Copy and rename `.env.example` file to `.env` at root of this project. Provide the `VK_CLIENT_ID` and
`VK_CLIENT_SECRET`.

Run the project:

```
./vendor/bin/drush runserver
```

Go to http://127.0.0.1:8888 and try to login via Vkontakte.

To login as drupal admin use `admin` with password `admin`.
