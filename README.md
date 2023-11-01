[
  {
    "kind": "transaction",
    "source": "tz1cZVbFLhGA3obUjFMamUBknEYUr5rcxX3g",
    "fee": "998",
    "counter": "20622791",
    "gas_limit": "6712",
    "storage_limit": "100",
    "amount": "0",
    "destination": "KT1GqQqgLji2T5QMfzoAXgDt9T7ur1LhqfpD",
    "parameters": {
      "entrypoint": "get_price",
      "value": {
        "string": "KT1KpFkAKgrAJNXZxhahFaTduTAoEc8jFpmQ%set_price"
      }
    },
    "metadata": {
      "balance_updates": [
        {
          "kind": "contract",
          "contract": "tz1cZVbFLhGA3obUjFMamUBknEYUr5rcxX3g",
          "change": "-998",
          "origin": "block"
        },
        {
          "kind": "accumulator",
          "category": "block fees",
          "change": "998",
          "origin": "block"
        }
      ],
      "operation_result": {
        "status": "applied",
        "storage": [
          {
            "prim": "Pair",
            "args": [
              {
                "int": "1698696044"
              },
              {
                "prim": "Pair",
                "args": [
                  {
                    "bytes": "01d496def47a3be89f5d54c6e6bb13cc6645d6e16600"
                  },
                  {
                    "bytes": "0115eb0104481a6d7921160bc982c5e0a561cd8a3a00"
                  }
                ]
              }
            ]
          },
          {
            "prim": "Pair",
            "args": [
              {
                "int": "380271689"
              },
              {
                "bytes": "01a3d0f58d8964bd1b37fb0a0c197b38cf46608d4900"
              }
            ]
          },
          {
            "int": "30012933581"
          },
          {
            "int": "78924975"
          }
        ],
        "consumed_milligas": "3173537",
        "storage_size": "1384"
      },
      "internal_operation_results": [
        {
          "kind": "transaction",
          "source": "KT1GqQqgLji2T5QMfzoAXgDt9T7ur1LhqfpD",
          "nonce": 5,
          "amount": "0",
          "destination": "KT1AafHA1C1vk959wvHWBispY9Y2f3fxBUUo",
          "parameters": {
            "entrypoint": "getTotalSupply",
            "value": {
              "prim": "Pair",
              "args": [
                {
                  "prim": "Unit"
                },
                {
                  "bytes": "015a85f1df71b0b71be9aac52decc629ce12f0879d007365745f6c70745f746f74616c5f737570706c79"
                }
              ]
            }
          },
          "result": {
            "status": "applied",
            "storage": [
              {
                "int": "9563"
              },
              {
                "int": "9564"
              },
              {
                "bytes": "01d496def47a3be89f5d54c6e6bb13cc6645d6e16600"
              },
              {
                "int": "380271689"
              }
            ],
            "consumed_milligas": "310569",
            "storage_size": "92188",
            "lazy_storage_diff": [
              {
                "kind": "big_map",
                "id": "9564",
                "diff": {
                  "action": "update",
                  "updates": []
                }
              },
              {
                "kind": "big_map",
                "id": "9563",
                "diff": {
                  "action": "update",
                  "updates": []
                }
              }
            ]
          }
        },
        {
          "kind": "transaction",
          "source": "KT1AafHA1C1vk959wvHWBispY9Y2f3fxBUUo",
          "nonce": 8,
          "amount": "0",
          "destination": "KT1GqQqgLji2T5QMfzoAXgDt9T7ur1LhqfpD",
          "parameters": {
            "entrypoint": "set_lpt_total_supply",
            "value": {
              "int": "380271689"
            }
          },
          "result": {
            "status": "applied",
            "storage": [
              {
                "prim": "Pair",
                "args": [
                  {
                    "int": "1698696044"
                  },
                  {
                    "prim": "Pair",
                    "args": [
                      {
                        "bytes": "01d496def47a3be89f5d54c6e6bb13cc6645d6e16600"
                      },
                      {
                        "bytes": "0115eb0104481a6d7921160bc982c5e0a561cd8a3a00"
                      }
                    ]
                  }
                ]
              },
              {
                "prim": "Pair",
                "args": [
                  {
                    "int": "380271689"
                  },
                  {
                    "bytes": "01a3d0f58d8964bd1b37fb0a0c197b38cf46608d4900"
                  }
                ]
              },
              {
                "int": "30012933581"
              },
              {
                "int": "78924975"
              }
            ],
            "consumed_milligas": "310699",
            "storage_size": "1384"
          }
        },
        {
          "kind": "transaction",
          "source": "KT1GqQqgLji2T5QMfzoAXgDt9T7ur1LhqfpD",
          "nonce": 6,
          "amount": "0",
          "destination": "KT1PWx2mnDueood7fEmfbBDKx1D9BAnnXitn",
          "parameters": {
            "entrypoint": "getBalance",
            "value": {
              "prim": "Pair",
              "args": [
                {
                  "bytes": "01d496def47a3be89f5d54c6e6bb13cc6645d6e16600"
                },
                {
                  "bytes": "015a85f1df71b0b71be9aac52decc629ce12f0879d007365745f76616c75655f746f6b656e5f62616c616e63655f6f66"
                }
              ]
            }
          },
          "result": {
            "status": "applied",
            "storage": [
              {
                "int": "31"
              },
              [
                {
                  "prim": "DUP"
                },
                {
                  "prim": "CAR"
                },
                {
                  "prim": "DIP",
                  "args": [
                    [
                      {
                        "prim": "CDR"
                      }
                    ]
                  ]
                },
                {
                  "prim": "DUP"
                },
                {
                  "prim": "DUP"
                },
                {
                  "prim": "CAR"
                },
                {
                  "prim": "DIP",
                  "args": [
                    [
                      {
                        "prim": "CDR"
                      }
                    ]
                  ]
                },
                {
                  "prim": "DIP",
                  "args": [
                    [
                      {
                        "prim": "DIP",
                        "args": [
                          {
                            "int": "2"
                          },
                          [
                            {
                              "prim": "DUP"
                            }
                          ]
                        ]
                      },
                      {
                        "prim": "DIG",
                        "args": [
                          {
                            "int": "2"
                          }
                        ]
                      }
                    ]
                  ]
                },
                {
                  "prim": "PUSH",
                  "args": [
                    {
                      "prim": "string"
                    },
                    {
                      "string": "code"
                    }
                  ]
                },
                {
                  "prim": "PAIR"
                },
                {
                  "prim": "PACK"
                },
                {
                  "prim": "GET"
                },
                {
                  "prim": "IF_NONE",
                  "args": [
                    [
                      {
                        "prim": "NONE",
                        "args": [
                          {
                            "prim": "lambda",
                            "args": [
                              {
                                "prim": "pair",
                                "args": [
                                  {
                                    "prim": "bytes"
                                  },
                                  {
                                    "prim": "big_map",
                                    "args": [
                                      {
                                        "prim": "bytes"
                                      },
                                      {
                                        "prim": "bytes"
                                      }
                                    ]
                                  }
                                ]
                              },
                              {
                                "prim": "pair",
                                "args": [
                                  {
                                    "prim": "list",
                                    "args": [
                                      {
                                        "prim": "operation"
                                      }
                                    ]
                                  },
                                  {
                                    "prim": "big_map",
                                    "args": [
                                      {
                                        "prim": "bytes"
                                      },
                                      {
                                        "prim": "bytes"
                                      }
                                    ]
                                  }
                                ]
                              }
                            ]
                          }
                        ]
                      }
                    ],
                    [
                      {
                        "prim": "UNPACK",
                        "args": [
                          {
                            "prim": "lambda",
                            "args": [
                              {
                                "prim": "pair",
                                "args": [
                                  {
                                    "prim": "bytes"
                                  },
                                  {
                                    "prim": "big_map",
                                    "args": [
                                      {
                                        "prim": "bytes"
                                      },
                                      {
                                        "prim": "bytes"
                                      }
                                    ]
                                  }
                                ]
                              },
                              {
                                "prim": "pair",
                                "args": [
                                  {
                                    "prim": "list",
                                    "args": [
                                      {
                                        "prim": "operation"
                                      }
                                    ]
                                  },
                                  {
                                    "prim": "big_map",
                                    "args": [
                                      {
                                        "prim": "bytes"
                                      },
                                      {
                                        "prim": "bytes"
                                      }
                                    ]
                                  }
                                ]
                              }
                            ]
                          }
                        ]
                      },
                      {
                        "prim": "IF_NONE",
                        "args": [
                          [
                            {
                              "prim": "PUSH",
                              "args": [
                                {
                                  "prim": "string"
                                },
                                {
                                  "string": "UStore: failed to unpack code"
                                }
                              ]
                            },
                            {
                              "prim": "FAILWITH"
                            }
                          ],
                          []
                        ]
                      },
                      {
                        "prim": "SOME"
                      }
                    ]
                  ]
                },
                {
                  "prim": "IF_NONE",
                  "args": [
                    [
                      {
                        "prim": "DROP"
                      },
                      {
                        "prim": "DIP",
                        "args": [
                          [
                            {
                              "prim": "DUP"
                            },
                            {
                              "prim": "PUSH",
                              "args": [
                                {
                                  "prim": "bytes"
                                },
                                {
                                  "bytes": "05010000000866616c6c6261636b"
                                }
                              ]
                            },
                            {
                              "prim": "GET"
                            },
                            {
                              "prim": "IF_NONE",
                              "args": [
                                [
                                  {
                                    "prim": "PUSH",
                                    "args": [
                                      {
                                        "prim": "string"
                                      },
                                      {
                                        "string": "UStore: no field fallback"
                                      }
                                    ]
                                  },
                                  {
                                    "prim": "FAILWITH"
                                  }
                                ],
                                []
                              ]
                            },
                            {
                              "prim": "UNPACK",
                              "args": [
                                {
                                  "prim": "lambda",
                                  "args": [
                                    {
                                      "prim": "pair",
                                      "args": [
                                        {
                                          "prim": "pair",
                                          "args": [
                                            {
                                              "prim": "string"
                                            },
                                            {
                                              "prim": "bytes"
                                            }
                                          ]
                                        },
                                        {
                                          "prim": "big_map",
                                          "args": [
                                            {
                                              "prim": "bytes"
                                            },
                                            {
                                              "prim": "bytes"
                                            }
                                          ]
                                        }
                                      ]
                                    },
                                    {
                                      "prim": "pair",
                                      "args": [
                                        {
                                          "prim": "list",
                                          "args": [
                                            {
                                              "prim": "operation"
                                            }
                                          ]
                                        },
                                        {
                                          "prim": "big_map",
                                          "args": [
                                            {
                                              "prim": "bytes"
                                            },
                                            {
                                              "prim": "bytes"
                                            }
                                          ]
                                        }
                                      ]
                                    }
                                  ]
                                }
                              ]
                            },
                            {
                              "prim": "IF_NONE",
                              "args": [
                                [
                                  {
                                    "prim": "PUSH",
                                    "args": [
                                      {
                                        "prim": "string"
                                      },
                                      {
                                        "string": "UStore: failed to unpack fallback"
                                      }
                                    ]
                                  },
                                  {
                                    "prim": "FAILWITH"
                                  }
                                ],
                                []
                              ]
                            },
                            {
                              "prim": "SWAP"
                            }
                          ]
                        ]
                      },
                      {
                        "prim": "PAIR"
                      },
                      {
                        "prim": "EXEC"
                      }
                    ],
                    [
                      {
                        "prim": "DIP",
                        "args": [
                          [
                            {
                              "prim": "SWAP"
                            },
                            {
                              "prim": "DROP"
                            },
                            {
                              "prim": "PAIR"
                            }
                          ]
                        ]
                      },
                      {
                        "prim": "SWAP"
                      },
                      {
                        "prim": "EXEC"
                      }
                    ]
                  ]
                }
              ],
              {
                "int": "1"
              },
              {
                "prim": "False"
              }
            ],
            "consumed_milligas": "1882809",
            "storage_size": "384950",
            "lazy_storage_diff": [
              {
                "kind": "big_map",
                "id": "31",
                "diff": {
                  "action": "update",
                  "updates": []
                }
              }
            ]
          }
        },
        {
          "kind": "transaction",
          "source": "KT1PWx2mnDueood7fEmfbBDKx1D9BAnnXitn",
          "nonce": 9,
          "amount": "0",
          "destination": "KT1GqQqgLji2T5QMfzoAXgDt9T7ur1LhqfpD",
          "parameters": {
            "entrypoint": "set_value_token_balance_of",
            "value": {
              "int": "30029949389"
            }
          },
          "result": {
            "status": "applied",
            "storage": [
              {
                "prim": "Pair",
                "args": [
                  {
                    "int": "1698696044"
                  },
                  {
                    "prim": "Pair",
                    "args": [
                      {
                        "bytes": "01d496def47a3be89f5d54c6e6bb13cc6645d6e16600"
                      },
                      {
                        "bytes": "0115eb0104481a6d7921160bc982c5e0a561cd8a3a00"
                      }
                    ]
                  }
                ]
              },
              {
                "prim": "Pair",
                "args": [
                  {
                    "int": "380271689"
                  },
                  {
                    "bytes": "01a3d0f58d8964bd1b37fb0a0c197b38cf46608d4900"
                  }
                ]
              },
              {
                "int": "30029949389"
              },
              {
                "int": "78924975"
              }
            ],
            "consumed_milligas": "310621",
            "storage_size": "1384"
          }
        },
        {
          "kind": "transaction",
          "source": "KT1GqQqgLji2T5QMfzoAXgDt9T7ur1LhqfpD",
          "nonce": 7,
          "amount": "0",
          "destination": "KT1GqQqgLji2T5QMfzoAXgDt9T7ur1LhqfpD",
          "parameters": {
            "entrypoint": "internal_get_price",
            "value": {
              "bytes": "017b3650608746267f288aa3350888143f550a2b99007365745f7072696365"
            }
          },
          "result": {
            "status": "applied",
            "storage": [
              {
                "prim": "Pair",
                "args": [
                  {
                    "int": "1698696959"
                  },
                  {
                    "prim": "Pair",
                    "args": [
                      {
                        "bytes": "01d496def47a3be89f5d54c6e6bb13cc6645d6e16600"
                      },
                      {
                        "bytes": "0115eb0104481a6d7921160bc982c5e0a561cd8a3a00"
                      }
                    ]
                  }
                ]
              },
              {
                "prim": "Pair",
                "args": [
                  {
                    "int": "380271689"
                  },
                  {
                    "bytes": "01a3d0f58d8964bd1b37fb0a0c197b38cf46608d4900"
                  }
                ]
              },
              {
                "int": "30029949389"
              },
              {
                "int": "78969721"
              }
            ],
            "consumed_milligas": "313905",
            "storage_size": "1384"
          }
        },
        {
          "kind": "transaction",
          "source": "KT1GqQqgLji2T5QMfzoAXgDt9T7ur1LhqfpD",
          "nonce": 10,
          "amount": "0",
          "destination": "KT1KpFkAKgrAJNXZxhahFaTduTAoEc8jFpmQ",
          "parameters": {
            "entrypoint": "set_price",
            "value": {
              "int": "633154066734"
            }
          },
          "result": {
            "status": "applied",
            "storage": {
              "prim": "Pair",
              "args": [
                {
                  "prim": "Pair",
                  "args": [
                    {
                      "int": "1887441"
                    },
                    {
                      "bytes": "015a85f1df71b0b71be9aac52decc629ce12f0879d00"
                    }
                  ]
                },
                {
                  "prim": "Pair",
                  "args": [
                    {
                      "int": "633154066734"
                    },
                    {
                      "int": "4"
                    }
                  ]
                }
              ]
            },
            "consumed_milligas": "307721",
            "storage_size": "605"
          }
        }
      ]
    }
  }
]
