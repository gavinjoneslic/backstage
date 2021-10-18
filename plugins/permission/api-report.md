## API Report File for "@backstage/plugin-permission"

> Do not edit this file. It is a report generated by [API Extractor](https://api-extractor.com/).

```ts
import { AuthorizeResult } from '@backstage/permission-common';
import { Permission } from '@backstage/permission-common';
import { default as React_2 } from 'react';
import { RouteProps } from 'react-router';

// Warning: (ae-missing-release-tag) "AsyncPermissionResult" is exported by the package, but it is missing a release tag (@alpha, @beta, @public, or @internal)
//
// @public (undocumented)
export class AsyncPermissionResult {
  constructor(allowed: boolean, pending: boolean);
  // (undocumented)
  static fromAuthorizeResult(
    authorizeResult: AuthorizeResult | undefined,
  ): AsyncPermissionResult;
  // (undocumented)
  isAllowed(): boolean;
  // (undocumented)
  isPending(): boolean;
  // (undocumented)
  static pending(): AsyncPermissionResult;
}

// Warning: (ae-missing-release-tag) "PermissionedRoute" is exported by the package, but it is missing a release tag (@alpha, @beta, @public, or @internal)
//
// @public (undocumented)
export const PermissionedRoute: ({
  permission,
  ...props
}: RouteProps & {
  permission: Permission;
}) => JSX.Element;

// Warning: (ae-missing-release-tag) "usePermission" is exported by the package, but it is missing a release tag (@alpha, @beta, @public, or @internal)
//
// @public (undocumented)
export const usePermission: (
  permission: Permission,
  resourceRef?: string | undefined,
) => AsyncPermissionResult;

// Warning: (ae-missing-release-tag) "WithPermission" is exported by the package, but it is missing a release tag (@alpha, @beta, @public, or @internal)
//
// @public (undocumented)
export const WithPermission: ({
  permission,
  children,
}: React_2.PropsWithChildren<{
  permission: Permission;
}>) => JSX.Element;

// (No @packageDocumentation comment for this package)
```