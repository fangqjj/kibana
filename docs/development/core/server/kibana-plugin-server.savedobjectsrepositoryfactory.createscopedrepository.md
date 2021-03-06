<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [kibana-plugin-server](./kibana-plugin-server.md) &gt; [SavedObjectsRepositoryFactory](./kibana-plugin-server.savedobjectsrepositoryfactory.md) &gt; [createScopedRepository](./kibana-plugin-server.savedobjectsrepositoryfactory.createscopedrepository.md)

## SavedObjectsRepositoryFactory.createScopedRepository property

Creates a [Saved Objects repository](./kibana-plugin-server.isavedobjectsrepository.md) that uses the credentials from the passed in request to authenticate with Elasticsearch.

<b>Signature:</b>

```typescript
createScopedRepository: (req: KibanaRequest, extraTypes?: string[]) => ISavedObjectsRepository;
```
