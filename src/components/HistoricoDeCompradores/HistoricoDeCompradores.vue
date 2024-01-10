<template>
    <div class="bg-white p-4 rounded-xl">
        <div class="sm:flex sm:items-center">
            <div class="sm:flex-auto">
                <h1 class="text-base font-medium leading-6 text-gray-900">
                    Histórico de compradores
                </h1>
            </div>
        </div>
        <div class="mt-8 flow-root">
            <div class="-mx-4 -my-2 overflow-x-auto sm:-mx-6 lg:-mx-8">
                <div class="inline-block min-w-full py-2 align-middle sm:px-6 lg:px-8">
                    <table class="min-w-full divide-y divide-gray-300">
                        <thead>
                            <tr>
                                <th
                                    scope="col"
                                    class="py-3.5 pl-4 pr-3 text-left text-sm font-semibold text-gray-900 sm:pl-0"
                                >
                                    ID
                                </th>
                                <th
                                    scope="col"
                                    class="px-3 py-3.5 text-left text-sm font-semibold text-gray-900"
                                >
                                    Data
                                </th>
                                <th
                                    scope="col"
                                    class="px-3 py-3.5 text-left text-sm font-semibold text-gray-900"
                                >
                                    Nome
                                </th>
                                <th
                                    scope="col"
                                    class="px-3 py-3.5 text-left text-sm font-semibold text-gray-900"
                                >
                                    Localização
                                </th>
                                <th
                                    scope="col"
                                    class="px-3 py-3.5 text-left text-sm font-semibold text-gray-900"
                                >
                                    Valor
                                </th>
                                <th
                                    scope="col"
                                    class="px-3 py-3.5 text-left text-sm font-semibold text-gray-900"
                                >
                                    Situação
                                </th>
                            </tr>
                        </thead>
                        <tbody class="divide-y divide-gray-200">
                            <tr>
                                <td
                                    class="whitespace-nowrap py-4 pl-4 pr-3 text-sm font-medium text-gray-900 sm:pl-0"
                                >
                                    #12345
                                </td>
                                <td class="whitespace-nowrap px-3 py-4 text-sm text-gray-500">
                                    02/08/2023
                                </td>
                                <td class="whitespace-nowrap px-3 py-4 text-sm text-gray-500">
                                    Roberto Santos
                                </td>
                                <td class="whitespace-nowrap px-3 py-4 text-sm text-gray-500">
                                    Rio Grande do Sul
                                </td>
                                <td class="whitespace-nowrap px-3 py-4 text-sm text-gray-500">
                                    R$ 15,00
                                </td>
                                <td
                                    class="whitespace-nowrap px-3 py-4 text-sm text-gray-500 flex items-center gap-2"
                                >
                                    <img src="/green_ellipse.png" alt="" /> Aprovado
                                </td>
                            </tr>
                            <tr>
                                <td
                                    class="whitespace-nowrap py-4 pl-4 pr-3 text-sm font-medium text-gray-900 sm:pl-0"
                                >
                                    #67890
                                </td>
                                <td class="whitespace-nowrap px-3 py-4 text-sm text-gray-500">
                                    03/08/2023
                                </td>
                                <td class="whitespace-nowrap px-3 py-4 text-sm text-gray-500">
                                    Beatriz Rodrigues
                                </td>
                                <td class="whitespace-nowrap px-3 py-4 text-sm text-gray-500">
                                    Salvador
                                </td>
                                <td class="whitespace-nowrap px-3 py-4 text-sm text-gray-500">
                                    R$ 15,00
                                </td>
                                <td
                                    class="whitespace-nowrap px-3 py-4 text-sm text-gray-500 flex items-center gap-2"
                                >
                                    <img src="/yellow_ellipse.png" alt="" /> Em análise
                                </td>
                            </tr>

                            <!-- More people... -->
                        </tbody>
                    </table>
                </div>
            </div>
        </div>
    </div>
</template>

<script setup></script>

<style lang="scss" scoped></style>
