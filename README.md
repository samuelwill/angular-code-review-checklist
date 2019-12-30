# Angular Code Review Checklist

### General
- [ ] Be smart
- [ ] Do the right thing

### Components
- [ ] Components are small, focused and only responsible for a small portion of the UI
- [ ] Developer understands the difference between containers and components and each component is only responsible for one of these roles
- [ ] All components declared using ChangeDetectionStrategy.OnPush
- [ ] Any unused lifecycle hooks have been removed

### Services
- [ ] HTTP services are separated from services that perform business logic
- [ ] HTTP services follow the naming convention: my-feature.data.service.ts, while business logic services follow: my-feature.service.ts

### NgRx
- [ ] The
